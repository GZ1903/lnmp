# lnmp环境一键部署

脚本适配环境：CentOS7+/RetHot7+、内存1G+ (推荐使用纯净机子)

极速部署（2-3min即可部署完成）

安装的软件版本:

```shell
Nginx 1.20.2
Mysql 5.6.51
PHP   7.3.33
redis 6.2.2
```

安装后环境适配V2board，sspabel，Zabbix，有道云，typecho，等等应用使用！

部署脚本：

```shell
yum -y install git wget && git clone https://gitee.com/gz1903/lnmp.git && chmod +x lnmp.sh && ./lnmp.sh
```

