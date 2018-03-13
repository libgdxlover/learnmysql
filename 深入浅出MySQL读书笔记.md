# 深入浅出Mysql读书笔记 #
----------
## 启动和关闭 MySQL 服务 ##
### 在Windows平台下启动和关闭MySQL服务
（1）启动服务：`mysqld --console`    
（2）关闭服务：`mysqladmin -uroot shutdown`
###  在Linux平台下启动和关闭MySQL服务
 (1) 启动服务：`./mysqld_safe &`  

    [root@localhost bin]# cd /usr/bin  
    [root@localhost bin]# ./mysqld_safe &  
    [1] 23013  
    [root@localhost bin]# Starting mysqld daemon with databases from /var/lib/mysql
### SQL基础

