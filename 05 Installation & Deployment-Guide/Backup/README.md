### 备份

为了保证系统的数据安全性，我们需要对 MySQL 配置库（ead）、系统库（app）以及 mongodb 存储库以及 EAD 程序包也进行备份。

### Mysql

Mysql 数据全量备份，通过 Shell 脚本，并在操作系统中加入计划任务进行数据备份。

### Mongodb

Mongodb 文件存储进行全量备份，通过 Shell 脚本，并在操作系统中加入计划任务进行数据备份。

### EAD 平台程序包备份

EAD 平台程序包备份有两种备份方式：

第一种：单独备份 war 包：拷贝 gbros-web.war 到备份文件夹下。
第二种：整体备份 ead 安装目录：拷贝 ead 目录到备份文件夹下。