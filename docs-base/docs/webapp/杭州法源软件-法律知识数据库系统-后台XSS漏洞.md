# 杭州法源软件 法律知识数据库系统 后台XSS漏洞

## 漏洞描述

杭州法源软件开发有限公司开发的实践教学平台系统下的法律知识数据库系统登录后台用户名处存在通用XSS漏洞

## 漏洞影响

```
杭州法源软件 法律知识数据库系统
```

## 网络测绘

```
icon_hash="2018105215" || title="实践教学平台 - 杭州法源软件开发有限公司"
```

## 漏洞复现



登录后台后更改用户名，使用 td标签 闭合



![](images/202202101857066.png)



![](images/202202101857457.png)