# Vulnerability Wiki

**【免责声明】本项目所涉及的技术、思路和工具仅供学习，任何人不得将其用于非法用途和盈利，不得将其用于非授权渗透测试，否则后果自行承担，与本项目无关。使用本项目前请先阅读 [法律法规](https://github.com/Threekiii/Awesome-Laws)。**

一个漏洞知识库，目前数量 1000+，支持本地/Docker 部署。

![](images/README/image-20240510143616156.png)

## 0x01 项目介绍

### 本项目由几个模块构成？

本项目收集漏洞均源于互联网。

- docs-base：核心漏洞库，基于项目 [Threekiii/Awesome-POC](https://github.com/Threekiii/Awesome-POC)。
	- 更新日志：[click here](https://github.com/Threekiii/Vulnerability-Wiki/tree/master/docs-base)
	- 目录总览：[click here](https://github.com/Threekiii/Vulnerability-Wiki/blob/master/docs-base/docs/_sidebar.md)
- docs-0sec：零组漏洞库， 已打包为 docs-0sec。
	- 下载 release：[click here](https://github.com/Threekiii/Vulnerability-Wiki/releases/download/v1.0/docs-0sec.zip)
- wooyun：wooyun 历史漏洞库，部署方式请参考 [v7hinc/wooyun](https://github.com/V7hinc/wooyun_final)（需要挂载目录，否则将无法显示图片）。

### 本项目解决了什么问题？

- 基于 docsify，快速部署 [Threekiii/Awesome-POC](https://github.com/Threekiii/Awesome-POC) 中的漏洞文档，按 docsify 规则更新目录层级，开箱即用，快速检索。
- 重构零组漏洞库，零组已于 2021 年停运，docs-0sec 内容来源于互联网 `.docx` 文件，已全部转换为 `.html` 格式。

## 0x02 前期准备

```shell
# git clone
git clone https://github.com/Threekiii/Vulnerability-Wiki.git
# fix coding error
yum install convmv
convmv -f gb2312 -t UTF-8 --notest -r ./Vulnerability-Wiki/ --replace
```

如果要部署 docs-0sec，请先下载 [release](https://github.com/Threekiii/Vulnerability-Wiki/releases/download/v1.0/docs-0sec.zip)，解压到本项目 docs-0sec 文件夹下。

## 0x03 服务部署

### 方式一 docsify 本地部署

#### 安装 docsify

- docsify 是一个快速文档生成器，官方 wiki https://docsify.js.org/#/zh-cn/
- 安装 `docsify-cli`：

```
npm i docsify-cli -g
```

#### 安装插件

- 侧边栏收起：https://github.com/iPeng6/docsify-sidebar-collapse
- 复制到剪贴板：https://github.com/jperasmus/docsify-copy-code/blob/master/README.md
- 代码高亮：https://github.com/PrismJS/prism
- 分页导航：https://github.com/imyelo/docsify-pagination#readme

#### 启动服务

进入 docs-base 和 docs-0sec 下的 docs 目录，执行以下命令分别启动服务：

```
docsify serve docs-base
docsify serve docs-0sec
```

服务启动后，分别访问对应的 http://your-ip:port 即可。

### 方式二 docker 部署单个项目

#### 部署 docs-base

进入 docs-base 目录，通过 Dockerfile 启动服务：

```shell
# docker build & run
cd ./Vulnerability-Wiki/docs-base
docker build -f Dockerfile -t threeki/vulnerability_wiki .
docker run -d -p 3001:3001 threeki/vulnerability_wiki:latest
```

服务启动后，访问 http://your-ip:3001 即可。

#### 部署 docs-0sec

进入 docs-0sec 目录，将下载的 release 解压到当前目录后，通过 Dockerfile 启动服务：

```shell
cd ./Vulnerability-Wiki/

# download docs-0sec release
wget https://github.com/Threekiii/Vulnerability-Wiki/releases/download/v1.0/docs-0sec.zip
unzip -o docs-0sec.zip

# docker build & run
cd docs-0sec
docker build -f Dockerfile -t threeki/vulnerability_wiki .
docker run -d -p 3001:3001 threeki/vulnerability_wiki:latest
```

服务启动后，访问 http://your-ip:3002 即可。

#### 部署 wooyun

wooyun 部署方式请参考 [v7hinc/wooyun](https://github.com/V7hinc/wooyun_final)（需要挂载目录，否则将无法显示图片），执行以下命令拉取镜像启动服务：

```shell
# docker build & run
docker pull v7hinc/wooyun
docker run --privileged=true --name wooyun -v ~/upload:/home/wwwroot/default/upload -p 3003:80 -dit v7hinc/wooyun:latest /bin/bash
```

服务启动后，访问 http://your-ip:3003 即可。

### 方式三 docker-compose 部署多个项目

通过 docker-compose.yml 部署三个 docs-base、docs-0sec 和 wooyun：

```shell
# dependencies
apt install docker docker-compose
git clone https://github.com/Threekiii/Vulnerability-Wiki.git
cd Vulnerability-Wiki

# download docs-0sec release
wget https://github.com/Threekiii/Vulnerability-Wiki/releases/download/v1.0/docs-0sec.zip
unzip -o docs-0sec.zip

# download wooyun image
docker pull v7hinc/wooyun

# create and start containers
docker-compose up -d

# stop services
docker-compose down
```

服务启动后，即可访问：

- docs-base：http://your-vps-ip:3001
- docs-0sec：http://your-vps-ip:3002
- wooyun：http://your-vps-ip:3003

## 0x04 Issues

### docker-compose 报错

 - [issue/5](https://github.com/Threekiii/Vulnerability-Wiki/issues/5)：~~若 docker-compose 部署时出现 cnpm 相关错误，请更改对应 Dockerfile，将 cnpm 改为 npm，再次尝试。~~ 已优化 Dockerfile，此类问题将不再发生。

### 404 error

- docs-0sec 可能遇到 404 报错，请先确认下载了 release 并解压到项目 docs-0sec 文件夹，数据准备好后再进行 `docker-compose`。若已经启动服务，则需要重新 `build`，解决方式请参考 [issue/6](https://github.com/Threekiii/Vulnerability-Wiki/issues/6) 。

### gbk 编码问题

- vps 部署可能出现乱码，可参考以下命令解决：

```
yum install convmv
convmv -f gb2312 -t UTF-8 --notest -r ./Vulnerability-Wiki/docs-base/docs --replace
```

## 0x05 更新日志

- 2024.05.01 优化 Dockerfile。
- 2024.04.01 重构目录，合并 vulhub 到各细分目录。
- 2022.12.05 图片本地化，修复 Dockerfile。
- 2022.08.24 更新部分漏洞，增加 Issues 解决方案。
- 2022.07.15 新增 [docs-0sec release](https://github.com/Threekiii/Vulnerability-Wiki/releases/download/v1.0/docs-0sec.zip) 。由于影响主项目加载及检索速度，0sec 独立为子项目。
- 2022.06.20 2.0 版本，重新划分漏洞分区，优化搜索策略。
- 2022.05.25 补全 peiqi 漏洞库中所有漏洞。
- 2022.05.13 引入 wooyun 漏洞库，部署方式改为 docker-compose。
