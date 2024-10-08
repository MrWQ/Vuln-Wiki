# Vulnerability Wiki

**【免责声明】本项目所涉及的技术、思路和工具仅供学习，任何人不得将其用于非法用途和盈利，不得将其用于非授权渗透测试，否则后果自行承担，与本项目无关。使用本项目前请先阅读 [法律法规](https://github.com/Threekiii/Awesome-Laws)。**

**【使用说明】**

- **建议直接跳转 [目录总览](_sidebar.md) 后使用 Ctrl+F 搜索**
- 2.0 版本重新划分漏洞分区，优化搜索策略
- 零组漏洞库 [docs-0sec](0sec/) 与乌云镜像站 [Wooyun](wooyun/) 请参考 [README](https://github.com/Threekiii/Vulnerability-Wiki) 单独部署

**【最近更新】**

- 2024.10.08
  - OpenPrinting-Cups-Browsed-PDD-FoomaticRIPCommandLine-参数导致远程命令执行漏洞-CVE-2024-47177.md
  
- 2024.09.18
  - Apache-OFBiz-SSRF-和远程代码执行漏洞-CVE-2024-45507.md
  - Apache-OFBiz-身份验证绕过导致远程代码执行-CVE-2024-38856.md
  - Apache-OFBiz-身份验证绕过导致远程代码执行-CVE-2024-45195.md
- 2024.09.14
  - 锐捷-NBR-1300G 路由器-越权 CLI 命令执行漏洞.md
  - 用友-ERP-NC-NCFindWeb-目录遍历漏洞.md
  - CactiEZ weathermap 插件任意文件写入漏洞.md
- 2024.07.18
  - Jetbrains-TeamCity-认证绕过导致远程命令执行漏洞-CVE-2023-42793.md（update）
  - JetBrains-TeamCity-身份验证绕过漏洞--CVE-2024-27198.md
- 2024.07.16
  - Nacos-认证绕过漏洞-CVE-2021-29441.md
  - Nacos-未授权接口命令执行漏洞-CVE-2021-29442.md
- 2024.07.04
  - GeoServer-属性名表达式前台代码执行漏洞-CVE-2024-36401.md
  - ShowDoc-3.2.5-SQL 注入漏洞.md
- 2024.07.02
  - Apache-APISIX-jwt-auth-插件存在-JWT-sceret-泄漏-CVE-2022-29266.md
- 2024.06.13
  - JumpServer-远程代码执行漏洞-CVE-2024-29201&CVE-2024-29202.md
- 2024.06.12
  - Apache-OFBiz-目录遍历致代码执行漏洞-CVE-2024-36104.md
  - PHP-CGI-Windows-平台远程代码执行漏洞-CVE-2024-4577.md
- 2024.06.03
  - Harbor-公开镜像仓库未授权访问-CVE-2022-46463.md
  - ShowDoc-前台任意文件上传-CNVD-2020-26585.md
  - 致远-OA-未授权短信验证码绕过重置密码漏洞.md
- 2024.05.29
  - PHP-8.1.0-dev-开发版本-zerodium-后门漏洞.md
  - PHP-XDebug-远程调试模式导致代码执行.md
  - PHP-imap-远程命令执行漏洞-CVE-2018-19518.md
  - PHP-利用-GNU-C-Iconv-将文件读取提升至-RCE-CVE-2024-2961.md
  - PHP-利用-phpinfo-包含临时文件-getshell.md
  - PHP-环境-XML 外部实体注入漏洞（XXE）.md
- 2024.05.27
  - AJ-Report-认证绕过与远程代码执行漏洞-CNVD-2024-15077.md
  - Nexus-Repository-Manager-3-未授权目录穿越漏洞-CVE-2024-4956.md
  - PDF.js-任意-JavaScript-代码执行-CVE-2024-4367.md
- 2024.05.06
  - JimuReport-FreeMarker-服务端模板注入命令执行-CVE-2023-4450.md
- 2024.04.22
  - kkFileView-ZipSlip-远程命令执行漏洞.md
  - Jeecg-jeecgFormDemoController-JNDI-代码执行漏洞-CVE-2023-49442.md
- 2024.04.07
  - pgAdmin-≤-6.16-无授权远程命令执行漏洞-CVE-2022-4223.md
  - pgAdmin-≤-7.6-后台远程命令执行漏洞-CVE-2023-5002.md
- 2024.04.01
  - DedeCMS-5.7-file_manage_control.php-文件包含-RCE-CVE-2023-2928.md
  - DedeCMS-5.7SP2-代码执行漏洞-CVE-2019-8933.md
  - DedeCMS-5.8.1-common.func.php-远程命令执行漏洞.md
  - Laravel Ignition 2.5.1 代码执行漏洞 CVE-2021-3129.md
  - Jenkins 远程代码执行漏洞 CVE-2019-1003000.md
- 2024.03.22
  - Jenkins-远程代码执行漏洞-CVE-2019-1003000.md
- 2024.03.07
  - OpenTSDB-命令注入漏洞-CVE-2023-25826.md
  - OpenTSDB-命令注入漏洞-CVE-2020-35476.md
- 2024.02.26
  - Adobe-ColdFusion-XML-反序列化命令执行漏洞-CVE-2023-29300.md
  - Adobe-ColdFusion-本地文件包含漏洞-CVE-2023-26360.md
  - CMS-Made-Simple-(CMSMS)-前台 SQL 注入漏洞-CVE-2019-9053.md
  - CMS-Made-Simple-(CMSMS)-前台代码执行漏洞-CVE-2021-26120.md
  - Confluence-OGNL 表达式注入命令执行漏洞-CVE-2023-22527.md
  - Jenkins-CLI-接口任意文件读取漏洞-CVE-2024-23897.md
  - Jetbrains-TeamCity-认证绕过导致远程命令执行漏洞-CVE-2023-42793.md
  - MeterSphere-v1.15.4-认证用户 SQL 注入漏洞-CVE-2021-45788.md
- 2024.01.31
  - 信呼 OA-qcloudCosAction.php-任意文件上传漏洞.md
  - Apache-Commons-Configuration-远程命令执行漏洞-CVE-2022-33980.md
- 2024.01.04
  - Apache-OFBiz-鉴权绕过导致命令执行-CVE-2023-51467.md
  - Apache-ActiveMQ-OpenWire-协议反序列化命令执行漏洞-CVE-2023-46604.md
- 2023.12.12
  - Apache-OFBiz-鉴权绕过导致命令执行-CVE-2023-51467.md
- 2023.12.04
  - Apache-ActiveMQ-Jolokia-后台远程代码执行漏洞-CVE-2022-41678.md
- 2023.11.20
  - Citrix-NetScaler-ADC-&-Gateway-信息泄露漏洞-CVE-2023-4966.md
- 2023.11.16
  - Milesight-Router-httpd.log-信息泄漏漏洞-CVE-2023-4714.md
  - 百为通达-智能流控路由器-open-远程命令执行漏洞.md
  - 大华-ICC 智能物联综合管理平台-readPic-任意文件读取漏洞.md
  - 锐捷-校园网自助服务系统-login_judge.jsf-任意文件读取漏洞.md
  - 思福迪-运维安全管理系统-test_qrcode_b-远程命令执行漏洞.md
  - 金蝶 OA-EAS 系统-uploadLogo.action-任意文件上传漏洞.md
  - 金蝶 OA-云星空-ScpSupRegHandler-任意文件上传漏洞.md
  - 蓝凌 EIS-智慧协同平台-api.aspx-任意文件上传漏洞.md
  - 用友-U8-cloud-upload.jsp-任意文件上传漏洞.md
- 2023.11.15
  - Atlassian-Confluence-server-info.action-登陆绕过漏洞-CVE-2023-22515.md
  - Casdoor-static-任意文件读取漏洞.md
  - CloudPanel-makefile-任意文件上传漏洞-CVE-2023-35885.md
  - EduSoho-教培系统-app_dev.php-任意读取漏洞.md
  - Richmail-企业邮箱-noCookiesMail-登陆绕过漏洞.md
  - Smartbi-RMIServlet-登陆绕过漏洞.md
  - 任我行-管家婆-订货易在线商城-SelectImage.aspx-任意文件上传漏洞.md
  - 锐起云-resetPwd-登陆绕过漏洞.md
  - 锐起云-xiazai-任意文件读取漏洞.md
  - 深信服-NGAF 下一代防火墙-loadfile.php-任意文件读取漏洞.md
  - 深信服-NGAF 下一代防火墙-login.cgi-远程命令执行漏洞.md
- 2023.10.30
  - Apache-ActiveMQ 远程代码执行.md
- 2023.10.08
  - librsvg-XInclude-文件包含漏洞-CVE-2023-38633.md
  - JumpServer 随机数种子泄露导致账户劫持漏洞-CVE-2023-42820.md
- 2023.08.28
  - PigCMS-action_flashUpload-任意文件上传漏洞.md
  - HIKVISION-综合安防管理平台-env-信息泄漏漏洞.md
  - HIKVISION-综合安防管理平台-files-任意文件上传漏洞.md
  - HIKVISION-综合安防管理平台-report-任意文件上传漏洞.md
  - Milesight-VPN-server.js-任意文件读取漏洞.md
  - 安恒-明御运维审计与风险控制系统-xmlrpc.sock-任意用户添加漏洞.md
  - 锐捷-NBR-路由器-fileupload.php-任意文件上传漏洞.md
  - 网神-SecGate-3600-防火墙-obj_app_upfile-任意文件上传漏洞.md
  - 网御-ACM 上网行为管理系统-bottomframe.cgi-SQL 注入漏洞.md
  - 用友-NC-Cloud-jsinvoke-任意文件上传漏洞.md
  - 用友-移动管理系统-uploadApk.do-任意文件上传漏洞.md
  - 1Panel-loadfile-后台文件读取漏洞.md
  - 辰信领创-辰信景云终端安全管理系统-login-SQL 注入漏洞.md
  - 汉得 SRM-tomcat.jsp-登陆绕过漏洞.md
  - 金盘-微信管理平台-getsysteminfo-未授权访问漏洞.md
  - 绿盟-NF 下一代防火墙-任意文件上传漏洞.md
  - 绿盟-SAS 堡垒机-Exec-远程命令执行漏洞.md
  - 绿盟-SAS 堡垒机-GetFile-任意文件读取漏洞.md
  - 绿盟-SAS 堡垒机-local_user.php-任意用户登录漏洞.md
  - 深信服-应用交付管理系统-login-远程命令执行漏洞.md
- 2023.08.27
  - 帆软报表-channel-远程命令执行漏洞.md
  - 泛微 OA-E-Office-uploadify-任意文件上传漏洞.md
  - 用友-U8-CRM 客户关系管理系统-getemaildata.php-任意文件上传漏洞.md
  - 用友-U8-CRM 客户关系管理系统-getemaildata.php-任意文件读取漏洞.md
  - 致远 OA-M1Server-userTokenService-远程命令执行漏洞.md
  - KubeOperator-kubeconfig-未授权访问漏洞-CVE-2023-22480.md
  - KubePi-JwtSigKey-登陆绕过漏洞-CVE-2023-22463.md
  - LiveBOS-ShowImage.do-任意文件读取漏洞.md
  - Metabase-validate-远程命令执行漏洞-CVE-2023-38646.md
  - OfficeWeb365-SaveDraw-任意文件上传漏洞.md
  - 亿赛通-电子文档安全管理系统-UploadFileFromClientServiceForClient-任意文件上传漏洞.md
  - 任我行-CRM-SmsDataList-SQL 注入漏洞.md
  - 企望制造-ERP-comboxstore.action-远程命令执行漏洞.md
  - 广联达-Linkworks-GetIMDictionary-SQL 注入漏洞.md
  - 广联达-Linkworks-msgbroadcastuploadfile.aspx-后台文件上传漏洞.md
  - 新开普-前置服务管理平台-service.action-远程命令执行漏洞.md
  - 明源云-ERP 系统-接口管家-ApiUpdate.ashx-任意文件上传漏洞.md
  - 深信服-DC 数据中心管理系统-sangforindex-XML 实体注入漏洞.md
  - 深信服-SG 上网优化管理系统-catjs.php-任意文件读取漏洞.md
  - 银达汇智-智慧综合管理平台-FileUp.aspx-任意文件上传漏洞.md
  - 飞企互联-FE 业务协作平台-ShowImageServlet-任意文件读取漏洞.md
  - 启明星辰-4A 统一安全管控平台-getMaster.do-信息泄漏漏洞.md
  - 大华-智慧园区综合管理平台-getFaceCapture-SQL 注入漏洞.md
  - 大华-智慧园区综合管理平台-user_getUserInfoByUserName.action-账号密码泄漏漏洞.md
  - 大华-智慧园区综合管理平台-video-任意文件上传漏洞.md
  - 安恒-明御安全网关-aaa_portal_auth_local_submit-远程命令执行漏洞.md
  - 锐捷-BCR 商业无线云网关-后台命令执行漏洞.md
  - 腾讯-企业微信-agentinfo-信息泄漏漏洞.md
- 2023.08.25
  - MeterSphere-插件接口未授权访问及远程代码执行.md
- 2023.08.03
  - Metabase 未授权 JDBC 远程代码执行漏洞-CVE-2023-38646.md
- 2023.08.01
  - Apache-RocketMQ-远程代码执行漏洞-CVE-2023-37582.md
  - 禅道-项目管理系统远程命令执行漏洞-CNVD-2023-02709.md
  - Apache-Commons-Text-远程代码执行漏洞-CVE-2022-42889.md
  - Fastjson-远程代码执行漏洞-CVE-2022-25845.md
  - Spring-Framework-安全绕过漏洞-CVE-2023-20860.md
  - ThinkPHP-命令执行漏洞-CNVD-2022-86535.md
  - 泛微 OA-E-Cology-ofsLogin.jsp-前台任意用户登录漏洞.md
  - 用友-NC-Cloud-远程代码执行漏洞-CNVD-C-2023-76801.md
  - Foxit-PDF-Reader-及-Editor-任意代码执行漏洞-CVE-2023-27363.md
  - Microsoft-Outlook-权限提升漏洞-CVE-2023-23397.md
  - Alibaba-Nacos-集群-Raft-反序列化漏洞-CNVD-2023-45001.md
  - Apache-Airflow-远程代码执行漏洞-CVE-2022-40127.md
  - Atlassian-Bitbucket-Data-Center-远程代码执行漏洞-CVE-2022-26133.md
  - KubeOperator_kubeconfig_ 未授权访问漏洞 _CVE-2023-22480.md
  - Smartbi-登录绕过漏洞.md
  - Smartbi-远程命令执行漏洞.md
  - 瑞友天翼应用虚拟化系统-AgentBoard.XGI-远程代码执行漏洞.md
  - 用友-畅捷通-T+-前台远程命令执行漏洞-QVD-2023-13615.md
  - 金蝶-K3Cloud-BinaryFormatter-反序列化漏洞.md
  - Apache-Druid-远程代码执行漏洞-QVD-2023-9629.md
  - Apache-Solr-代码执行漏洞-CNVD-2023-27598.md
- 2023.07.27
  - 泛微 OA e-cology FileDownloadForOutDoc 前台 SQL 注入漏洞.md
  - Gitlist-0.6.0-远程命令执行漏洞-CVE-2018-1000533.md
  - JBoss-5.x6.x-反序列化漏洞-CVE-2017-12149.md
  - Ruby-NetFTP-模块命令注入漏洞-CVE-2017-17405.md
  - Apache-Shiro-1.6.0-身份认证绕过漏洞-CVE-2020-13933.md
- 2023.07.17
  - K8s-etcd 未授权访问.md
  - Spring-Cloud-Config-目录遍历漏洞-CVE-2019-3799.md
  - Atlassian-Confluence-敏感信息泄露-CVE-2021-26085.md
  - Atlassian-Jira-敏感信息泄露-CVE-2021-26086.md
- 2023.07.11
  - Adminer-ElasticSearch-和-ClickHouse-错误页面 SSRF 漏洞-CVE-2021-21311.md
  - Adminer-远程文件读取-CVE-2021-43008.md
- 2023.07.05
  - 致远 OA-wpsAssistServlet-任意文件上传漏洞.md
  - 蓝凌 OA-treexml.tmpl-远程命令执行漏洞.md
  - Apache-Axis-远程代码执行漏洞-CVE-2019-0227.md
  - 用友-畅捷通 T+-GetStoreWarehouseByStore-远程命令执行漏洞.md
  - 霆智科技-VA 虚拟应用平台-任意文件读取漏洞.md
  - 宏景-HCM-codesettree-SQL 注入漏洞-CNVD-2023-0874.md
  - nginxWebUI-runCmd-远程命令执行漏洞.md
  - Atlassian-Jira-Server-及-Data-Center-信息泄露漏洞-CVE-2020-14179.md
  - Atlassian-Jira-Mobile-Plugin-SSRF 漏洞-CVE-2022-26135.md
  - 开发语言漏洞/JDWP 调试接口-RCE-漏洞.md
  - 大华-智慧园区综合管理平台-user_save.action-任意文件上传漏洞.md
  - 大华 城市安防监控系统平台管理 attachment_downloadByUrlAtt.action 任意文件下载漏洞.md
  - HIKVISION-iVMS-8700 综合安防管理平台-upload.action-任意文件上传漏洞.md
  - HIKVISION-iVMS-8700 综合安防管理平台-download-任意文件下载漏洞.md
  - Discuz!X3.4-后台修改 UCenter 配置 getshell 漏洞.md
  - VMware-vCenter-Server-任意文件上传漏洞-CVE-2021-22005.md
- 2023.06.19
  - GeoServer-OGC-Filter-SQL 注入漏洞-CVE-2023-25157.md
  - Openfire 管理后台认证绕过漏洞-CVE-2023-32315.md
- 2023.06.05
  - Apache-RocketMQ-远程命令执行漏洞-CVE-2023-33246.md
- 2023.06.01
  - Apache-RocketMQ-RCE-漏洞-CVE-2023-33246.md
  - PbootCMS-V3.1.2-正则绕过-RCE-漏洞.md
  - 禅道-V16.5-SQL-注入-CNVD-2022-42853.md
  - H3C-企业路由器（ER、ERG2、GR 系列）任意用户登录漏洞.md
  - HIKVISION 综合安防管理平台 applyCT Fastjson 远程命令执行漏洞.md
  - 安恒-明御安全网关-命令执行-任意文件读取漏洞.md
  - 蓝凌 OA admin.do JNDI 远程命令执行.md
  - 用友时空-KSOA-V9.0-文件上传漏洞.md
  - 操作系统漏洞/Linux-sudo 权限提升漏洞-CVE-2023-22809.md
- 2023.05.22
  - PHPStudy-后台管理页面-one-click-RCE.md
  - 开发语言漏洞/Python-pip-install-RCE-漏洞-CVE-2013-1629.md
- 2023.05.04
  - Apache-Druid-代码执行漏洞-CVE-2021-25646.md
  - Apache-Kafka-Clients-LDAP 注入漏洞-CVE-2023-25194.md
  - Apache-Shiro-认证绕过漏洞-CVE-2010-3863.md
  - InfluxDB-JWT-认证绕过漏洞-CVE-2019-20933.md
  - MinIO 集群模式信息泄露漏洞-CVE-2023-28432.md
  - ThinkPHP5-5.0.22-5.1.29-远程代码执行漏洞.md
  - ThinkPHP-多语言本地文件包含漏洞.md
  - V2board-1.6.1-提权漏洞.md
  - JeecgBoot-企业级低代码平台-qurestSql-SQL 注入漏洞-CVE-2023-1454.md
  - KubePi-LoginLogsSearch-未授权访问漏洞-CVE-2023-22478.md
  - KubeOperator-kubeconfig-未授权访问漏洞-CVE-2023-22480.md
  - Apache-Superset-SECRET_KEY-未授权访问漏洞-CVE-2023-27524.md
- 2023.04.24
  - Metersphere-file-任意文件读取漏洞-CVE-2023-25573.md
  - MeterSphere-customMethod-远程命令执行漏洞.md
  - PowerJob-list-信息泄漏漏洞-CVE-2023-29923.md
- 2023.04.18
  - Apache-Spark-未授权访问漏洞.md
  - Atlassian-Jira-模板注入漏洞-CVE-2019-11581.md
  - Gogs-任意用户登录漏洞-CVE-2018-18925.md
  - HTTPoxy-CGI-漏洞-CVE-2016-5385.md
  - Java-RMI-Registry-反序列化漏洞 (jdk8u232_b09).md
  - Jenkins-CI-远程代码执行漏洞-CVE-2017-1000353.md
  - Joomla-3.4.5-反序列化漏洞-CVE-2015-8562.md
  - Laravel-Ignition-2.5.1-代码执行漏洞-CVE-2021-3129.md
  - PostgreSQL-提权漏洞-CVE-2018-1058.md
  - Rocket-Chat-MongoDB-注入漏洞-CVE-2021-22911.md
  - Weblogic-弱口令 + 前台任意文件读取.md
  - 2023.04.17
  - MinIO-verify-敏感信息泄漏漏洞-CVE-2023-28432.md
  - 才茂通信-网关-formping-远程命令执行漏洞.md
  - 泛微 OA-v9-E-Cology-browser.jsp-SQL 注入漏洞.md
  - Alibaba-Nacos-secret.key 默认密钥-未授权访问漏洞.md
  - Alibaba-otter-manager 分布式数据库同步系统信息泄漏-CNVD-2021-16592.md
  - EasyImage-down.php-任意文件读取漏洞.md
  - EasyImage-manager.php-后台任意文件上传漏洞.md
  - Go-fastdfs-GetClientIp-未授权访问漏洞.md
  - Go-fastdfs-upload-任意文件上传漏洞-CVE-2023-1800.md
  - MLflow-get-artifact-任意文件读取漏洞-CVE-2023-1177.md
- 2023.04.10
  - Joomla 权限绕过漏洞-CVE-2023-23752.md
- 2023.03.28
  - JBoss 5.x/6.x-反序列化漏洞-CVE-2017-12149.md
  - PHP-FPM-远程代码执行漏洞-CVE-2019-11043.md
  - 操作系统漏洞/Windows 远程桌面服务漏洞-CVE-2019-0708.md
  - Weblogic 二次反序列化漏洞-CVE-2021-239.md
  - ElasticSearch-Groovy-沙盒绕过-&-代码执行漏洞 CVE-2015-1427.md
- 2023.03.14
  - Microsoft-Word-远程代码执行漏洞-CVE-2023-21716.md
  - 紫光档案管理系统 upload.html-后台文件上传漏洞.md
  - 拓尔思-MAS-testCommandExecutor.jsp-远程命令执行漏洞.md
  - Joomla application-未授权访问漏洞 CVE-2023-23752.md
  - O2OA open 后台任意文件读取漏洞.md
  - 联软安界 UniSDP 软件定义边界系统 commondRetSt 命令执行漏洞.md
  - 网神 SecIPS 3600 debug_info_export 任意文件下载漏洞.md
  - 网康 NS-ASG 安全网关 index.php 远程命令执行漏洞.md
  - 网康 下一代防火墙 HeartBeat.php 远程命令执行漏洞.md
  - 金山 VGM 防毒墙 downFile.php 任意文件读取漏洞.md
  - Panabit iXCache date_config 后台命令执行漏洞.md
  - Panabit Panalog sy_addmount.php 远程命令执行漏洞.md
- 2023.03.09
  - SolarView-Compact-命令注入漏洞-CVE-2022-40881.md
- 2023.03.06
  - ElasticSearch-目录穿越漏洞-CVE-2015-3337.md
  - Hashicorp-Consul-Service-API 远程命令执行漏洞.md
  - Jenkins-script-未授权远程命令执行漏洞.md
- 2023.02.28
  - Weblogic 未授权远程代码执行漏洞-CVE-2023-21839.md
  - Atlassian-Questions-For-Confluence-身份认证绕过漏洞-CVE-2022-26138.md
  - VMware-Spring-Security-身份认证绕过漏洞-CVE-2022-22978.md
  - K8s-API-Server 未授权命令执行.md
  - Ueditor 编辑器漏洞总结.md
- 2023.02.06
  - ImageMagick 任意文件读取漏洞-CVE-2022-44268.md
- 2022.12.28
  - Cacti 前台命令注入漏洞 CVE-2022-46169.md
- 2022.12.26
  - 应用 MySQL-UDF 提权.md
- 2022.12.09
  - Apache ActiveMQ 反序列化漏洞 CVE-2015-5254.md
  - 74cms v4.2.1 v4.2.129 后台 getshell 漏洞.md
  - 74cms v5.0.1 后台跨站请求伪造漏洞 CVE-2019-11374.md
  - Apache ActiveMQ 信息泄漏漏洞 CVE-2017-15709.md
- 2022.12.06
  - CmsEasy crossall_act.php SQL 注入漏洞.md
  - CmsEasy language_admin.php 后台命令执行漏洞.md
  - CmsEasy update_admin.php 后台任意文件上传漏洞.md
  - Discuz!X 3.4 admincp_setting.php 后台 SQL 注入漏洞.md
  - TypesetterCMS 后台任意文件上传.md
  - WeiPHP5.0 download_imgage 前台文件任意读取 CNVD-2020-68596.md
  - WeiPHP5.0 任意用户 Cookie 伪造 CNVD-2021-09693.md
  - 华宜互联 硬编码超级管理员漏洞.md
  - 禅道 11.6 api-getModel-api-getMethod-filePath 任意文件读取漏洞.md
  - 禅道 11.6 api-getModel-api-sql-sql 后台 SQL 注入漏洞.md
  - 禅道 11.6 api-getModel-editor-save-filePath 任意文件写入漏洞.md
  - 禅道 12.4.2 CSRF 漏洞 CNVD-2020-68552.md
  - 禅道 12.4.2 后台任意文件上传漏洞 CNVD-C-2020-121325.md
  - 泛微 OA DBconfigReader.jsp 数据库配置信息泄漏漏洞.md
  - 泛微 OA E-Bridge saveYZJFile 任意文件读取漏洞.md
  - 泛微 OA E-Cology BshServlet 远程代码执行漏洞 CNVD-2019-32204.md
  - 泛微 OA E-cology KtreeUploadAction 任意文件上传.md
  - 泛微 OA WorkflowCenterTreeData SQL 注入漏洞.md
  - 用友 GRP-U8 Proxy SQL 注入 CNNVD-201610-923.md
  - 致远 OA A8 htmlofficeservlet 任意文件上传漏洞.md
  - 致远 OA getSessionList.jsp Session 泄漏漏洞.md
  - 通达 OA v11.2 upload.php 后台任意文件上传漏洞.md
  - 通达 OA v11.5 login_code.php 任意用户登录.md
  - Citrix XenMobile 任意文件读取 CVE-2020-8209.md
  - 天融信 TopApp-LB SQL 注入漏洞.md
  - 天融信 TopApp-LB 命令执行漏洞.md
  - 天融信 TopApp-LB 系统 任意登陆.md
  - 宝塔 phpmyadmin 未授权访问漏洞.md
  - 深信服 EDR c.php 远程命令执行漏洞 CNVD-2020-46552.md
  - 深信服 EDR 后台任意用户登陆漏洞.md
  - Apache Cocoon XML 注入 CVE-2020-11991.md
  - Apache Kylin CubeService.java 命令注入漏洞 CVE-2020-1956.md
  - Apache Kylin DiagnosisController.java 命令注入漏洞 CVE-2020-13925.md
  - Apache Mod_jk 访问控制权限绕过 CVE-2018-11759.md
  - Apache Shiro 小于 1.2.4 反序列化漏洞 CVE-2016-4437.md
  - Apache Solr JMX 服务 RCE CVE-2019-12409.md
  - Apache Solr RCE 未授权上传漏洞 CVE-2020-13957.md
  - Apache Solr RCE 远程命令执行漏洞 CVE-2017-12629.md
  - Apache Solr Velocity 模板远程执行 CVE-2019-17558.md
  - Apache Solr XXE 漏洞 CVE-2017-12629.md
  - Apache Solr 任意文件读取漏洞.md
  - Apache Solr 远程执行漏洞 CVE-2019-0193.md
  - Apache Tomcat AJP 文件包含漏洞 CVE-2020-1938.md
  - Apache Tomcat 远程代码执行漏洞 CVE-2017-12615.md
  - JBoss 4.x JBossMQ JMS 反序列化漏洞 CVE-2017-7504.md
  - Nginx 越界读取缓存漏洞 CVE-2017-7529.md
  - Weblogic XMLDecoder 远程代码执行漏洞 CVE-2017-10271.md
  - Microsoft Exchange 远程命令执行 CVE-2021-27065 26857 26858 27065.md
  - OpenSSL 心脏滴血漏洞 CVE-2014-0160.md
  - Redis 小于 5.0.5 主从复制 RCE.md
  - WordPress WP_Query SQL 注入漏洞 CVE-2022-21661.md
  - Cisco ASA 设备 任意文件读取漏洞 CVE-2020-3452.md
  - D-LINK DAP-2020 webproc 任意文件读取漏洞 CVE-2021-27250.md
  - iKuai 后台任意文件读取漏洞.md
  - 锐捷 RG-UAC 账号密码信息泄露 CNVD-2021-14536.md
  - BloofoxCMS 0.5.2.1 存储型 XSS.md
  - Discuz 3.4 最新版后台 getshell.md
  - Fuel CMS 1.4.1 远程代码执行漏洞.md
  - Joomla 目录遍历及远程代码执行漏洞 CVE-2021-23132.md
  - JunAms 内容管理系统文件上传漏洞 CNVD-2020-24741.md
  - OneBlog 开源博客管理系统 远程命令执行漏洞.md
  - UCMS 文件上传漏洞 CVE-2020-25483.md
  - Cacti SQL 注入漏洞 CVE-2020-14295.md
  - Coremail 路径遍历与文件上传漏洞.md
  - GitLab 任意文件读取导致 RCE CVE-2020-10977.md
  - ShopXO 任意文件读取漏洞 CNVD-2021-15822.md
  - ShowDoc 前台文件上传漏洞.md
  - phpMyAdmin 后台 SQL 注入 CVE-2020-26935.md
  - Apache Solr Replication handler SSRF CVE-2021-27905.md
  - Apache Solr stream.url 任意文件读取漏洞.md
  - Apache Velocity 远程代码执行 CVE-2020-13936.md
  - FastAdmin 远程代码执行漏洞.md
  - Jackson-databind SSRF&RCE CVE-2020-36179~36182.md
  - Jackson-databind 远程代码执行 CVE-2019-12384.md
  - XStream SSRF 反序列化漏洞 CVE-2020-26258.md
  - XStream 任意文件删除 反序列化漏洞 CVE-2020-26259.md
  - Consul Docker images 空密码登录漏洞 CVE-2020-29564.md
  - Microsoft Exchange Server 远程执行代码漏洞 CVE-2020-17083.md
  - Microsoft Exchange 信息泄露漏洞 CVE-2020-17143.md
  - Microsoft Exchange 远程命令执行 CVE-2021-27065 26857 26858.md
  - SaltStack Minion 命令注入漏洞 CVE-2021-31607.md
  - Saltstack 未授权 RCE 漏洞 CVE-2021-25281~25283.md
  - C-Lodop 打印机任意文件读取漏洞.md
  - D-Link DIR-802 命令注入漏洞 CVE-2021-29379.md
  - D-Link DIR-841 命令注入漏洞 CVE-2021-28143.md
  - D-Link DIR-846 命令注入漏洞 CVE-2020-27600.md
  - JumpServer 远程命令执行漏洞.md
  - TG8 防火墙 RCE 及密码泄漏漏洞.md
  - TP-Link AC1750 预认证远程代码执行漏洞 CVE-2021-27246.md
  - TP-Link TL-WR841N 远程代码执行漏洞 CVE-2020-35576.md
- 2022.12.07
  - ZZZCMS parserSearch 远程命令执行漏洞.md
  - Webmin 多个高危漏洞 CVE-2021-31760~62.md
  - Weblogic Server 远程代码执行漏洞 CVE-2020-14756.md
  - VMware View Planner 未授权 RCE CVE-2021-21978.md
  - VMware vCenter Server 服务器端请求伪造漏洞 CVE-2021-21973.md
  - VMware vCenter Server 远程代码执行漏洞 CVE-2021-21972.md
  - Wazuh Manager 代码执行漏洞 CVE-2021-26814.md
  - WordPress Elementor Page Builder Plus 身份验证绕过 CVE-2021-24175.md
  - WordPress File Manager＜6.9 RCE CVE-2020-25213.md
  - WordPress SuperForms 4.9 任意文件上传到远程代码执行.md
- 2022.12.05
  - 启明星辰 天清汉马 USG 防火墙 逻辑缺陷漏洞 CNVD-2021-12793
  - 腾达 路由器 D151D31 未经身份验证的配置下载
  - 腾达 路由器 AC11 堆栈缓冲区溢出 CVE-2021-31758
  - 锐捷 Smartweb 管理系统 密码信息泄露漏洞 CNVD-2021-17369
  - 华硕 GT-AC2900 身份验证绕过 CVE-2021-32030
  - 碧海威 L7 多款产品 后台命令执行漏洞
  - iKuai 后台任意文件读取漏洞
  - 员工管理系统 Employee Management System 1.0 身份验证绕过
  - 金山 V8 V9 终端安全系统 文件上传漏洞
  - 阿里巴巴 otter manager 分布式数据库同步系统信息泄漏 CNVD-2021-16592
  - Adminer-SSRF 漏洞 CVE-2021-21311
  - Adobe ColdFusion 远程代码执行漏洞 CVE-2021-21087
  - Afterlogic Aurora & WebMail Pro 任意文件读取 CVE-2021-26294
  - Afterlogic Aurora & WebMail Pro 文件上传漏洞 CVE-2021-26293
  - 用友 NC FileReceiveServlet 反序列化 RCE 漏洞
  - 泛微 OA E-cology WorkflowServiceXml RCE
  - 泛微 OA E-cology KtreeUploadAction 任意文件上传
  - 微信客户端 远程命令执行漏洞
  - Apache OFBiz RMI Bypass RCE CVE-2021-29200
  - Apache NiFi Api 远程代码执行 RCE
  - Apache Druid 远程代码执行漏洞 CVE-2021-26919
  - Apache Druid 远程代码执行漏洞 CVE-2021-25646
  - Apache OFBiz 反序列化 CVE-2021-30128
  - Apache OfBiz 服务器端模板注入 SSTI
  - Apache OfBiz 远程代码执行 RCE
  - Anchor CMS 0.12.7 跨站请求伪造 CVE-2020-23342
- 2022.11.30
  - WebLogic T3 反序列化漏洞 CVE-2016-3510
  - Apache Tomcat RCE via JSP Upload Bypass
  - Apache Tomcat AJP 文件包含漏洞 CVE-2020-1938
  - Jenkins XStream 反序列化漏洞 CVE-2016-0792
  - Jenkins 远程代码执行漏洞 CVE-2015-8103
  - Citrix 远程命令执行漏洞 CVE-2019-19781
  - Weblogic 任意文件上传漏洞 CVE-2018-2894
  - Weblogic 10.3.6 'wls-wsat' XMLDecoder 反序列化漏洞 CVE-2017-10271
  - Shellshock 破壳漏洞 CVE-2014-6271
  - Apache Log4j2 lookup JNDI 注入漏洞 CVE-2021-44228
  - JBoss JMXInvokerServlet 反序列化漏洞 CVE-2015-7501
  - Docker daemon api 未授权访问漏洞 RCE
  - Struts2 S2-057 远程代码执行漏洞 CVE-2018-11776
  - Struts2 S2-052 远程代码执行漏洞 CVE-2017-9805
  - Struts2 S2-045 远程代码执行漏洞 CVE-2017-5638
  - Struts2 S2-016 远程代码执行漏洞 CVE-2013-2251
- 2022.11.25
  - YApi NoSQL 注入导致远程命令执行漏洞
  - CouchDB Erlang 分布式协议代码执行 CVE-2022-24706
- 2022.10.24
  - Dogtag PKI XML 实体注入漏洞 CVE-2022-2414
  - Dolibarr edit.php 远程命令执行漏洞 CVE-2022-40871
  - Fortinet FortiOS admin 远程命令执行漏洞 CVE-2022-40684
- 2022.10.17
  - 用友 畅捷通远程通 GNRemote.dll SQL 注入漏洞
  - AVEVA InTouch 安全网关 AccessAnywhere 任意文件读取漏洞 CVE-2022-23854
  - Dapr Dashboard configurations 未授权访问漏洞 CVE-2022-38817
  - 应用 WordPress All-in-One Video Gallery video.php 任意文件读取漏洞 CVE-2022-2633
- 2022.10.11
  - Apache APISIX Dashboard API 权限绕过导致 RCE CVE-2021-45232
- 2022.10.08
  - GLPI htmLawedTest.php 远程命令执行漏洞 CVE-2022-35914
  - Atlassian Bitbucket archive 远程命令执行漏洞 CVE-2022-36804
  - 通达 OA v11.9 getdata 任意命令执行漏洞
  - 泛微 OA E-Office OfficeServer.php 任意文件上传漏洞
  - Laravel Filemanager 插件 download 任意文件读取漏洞 CVE-2022-40734
- 2022.09.13
  - 泛微 OA E-Cology jqueryFileTree.jsp 目录遍历漏洞
  - 万户 OA DocumentEdit.jsp SQL 注入漏洞
  - 万户 OA TeleConferenceService XXE 注入漏洞
  - 万户 OA DownloadServlet 任意文件读取漏洞
  - FLIR-AX8-res.php-后台命令执行漏洞
  - FLIR-AX8 download.php 任意文件下载
  - Linux-openvswitch 权限提升漏洞-CVE-2022-2639
  - muhttpd 任意文件读取漏洞 CVE-2022-31793
  - 用友 畅捷通 T+ Upload.aspx 任意文件上传漏洞
- 2022.09.09
  - Apache Spark doAs 远程命令执行漏洞 CVE-2022-33891
  - 用友 畅捷通 T+ DownloadProxy.aspx 任意文件读取漏洞
  - 漏洞相关用友 畅捷通 T+ RecoverPassword.aspx 管理员密码修改漏洞
- 2022.08.29
  - O2OA invoke 后台远程命令执行漏洞 CNVD-2020-18740
  - Webgrind fileviewer.phtml 任意文件读取漏洞 CVE-2018-12909
  - Webmin password_change.cgi 远程命令执行漏洞 CVE-2019-15107
  - Webmin rpc.cgi 后台远程命令执行漏洞 CVE-2019-15642
  - Webmin update.cgi 后台远程命令执行漏洞 CVE-2022-0824
- 2022.08.24
  - 万户 OA OfficeServer.jsp 任意文件上传漏洞
  - 泛微 OA E-Cology VerifyQuickLogin.jsp 任意管理员登录漏洞
  - 用友 GRP-U8 UploadFileData 任意文件上传漏洞
  - 致远 OA wpsAssistServlet 任意文件上传漏洞
  - 致远 OA 帆软组件 ReportServer 目录遍历漏洞
  - NPS auth_key 未授权访问漏洞
  - Roxy-Wi options.py 远程命令执行漏洞 CVE-2022-31137
  - HIKVISION 综合安防管理平台 applyCT Fastjson 远程命令执行漏洞
  - Teleport 堡垒机 do-login 任意用户登录漏洞
  - Teleport 堡垒机 get-file 后台任意文件读取漏洞
  - 安恒 明御 WEB 应用防火墙 report.php 任意用户登录漏洞
- 2022.07.15
  - Django-Trunc(kind)-and-Extract(lookup_name)-SQL 注入漏洞-CVE-2022-34265
- 2022.07.06
  - 应用 WordPress-Simple-File-List-ee-downloader.php-任意文件读取漏洞-CVE-2022-1119
- 2022.07.05
  - Grafana 管理后台 SSRF
- 2022.06.23
  - 应用 WordPress-WP_Query-SQL 注入漏洞-CVE-2022-21661
  - Linux eBPF 权限提升漏洞 CVE-2022-23222
- 2022.06.06
  - Confluence OGNL 表达式注入命令执行漏洞-CVE-2022-26134
- 2022.05.17
  - Metabase 任意文件读取漏洞-CVE-2021-41277

## 声明

本项目收集漏洞均源于互联网，主要来自以下项目：

- Vulhub：https://github.com/vulhub
- Vulhub 复现：https://github.com/Threekiii/Vulhub-Reproduce
- Peiqi：https://github.com/PeiQi0/PeiQi-WIKI-Book
- EdgeSecurity： https://github.com/EdgeSecurityTeam/Vulnerability
- 0sec：零组漏洞库。零组已于 2021 年停运。内容来源于互联网.docx 文件，已全部转换为.html 文件。
- Wooyun：乌云漏洞库。乌云已于 2016 年停运，镜像参考 https://github.com/V7hinc/wooyun_final
