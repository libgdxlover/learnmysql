# 深入浅出Mysql读书笔记 #
----------
## 启动和关闭 MySQL 服务 ##
### 在Windows平台下启动和关闭MySQL服务
（1）启动服务：通过执行exe `mysqld --console` 或者命名行`net start mysql`   
（2）关闭服务：`mysqladmin -uroot shutdown`或者命名行`net stop mysql`
###  在Linux平台下启动和关闭MySQL服务  
  （1）启动服务：`mysqld_safe &`  
  （2）关闭服务：`mysqladmin -uroot shutdown`  
如果 MySQL 是用 RPM 包安装的，则启动和关闭 MySQL 服务过程如下。  
（1）启动服务：`service mysql start`  
如果在启动状态，需要重启服务，可以用以下命令直接重启，而不需要先关闭再启动：`service mysql restart`  
（2）关闭服务：`service mysql stop` 
## SQL基础
## MySQL 支持的数据类型 ##
## MySQL 中的运算符 ##
## 常用函数 ##
## 字符串函数 ##
| 函数         | 功能       |
| ------------- |:-------------:| 
| CANCAT(S1,S2,…Sn) |连接 S1,S2,…Sn 为一个字符串|
| INSERT(str,x,y,instr) |将字符串 str 从第 x 位置开始，y 个字符长的子串替换为字符串 instr   |
|LOWER(str) |将字符串 str 中所有字符变为小写|
|UPPER(str) |将字符串 str 中所有字符变为大写|
|LEFT(str ,x) |返回字符串 str 最左边的 x 个字符|
|RIGHT(str,x) |返回字符串 str 最右边的 x 个字符|
|LPAD(str,n ,pad)| 用字符串 pad 对 str 最左边进行填充，直到长度为 n 个字符长度|
|RPAD(str,n,pad)| 用字符串 pad 对 str 最右边进行填充，直到长度为 n 个字符长度|
|LTRIM(str) |去掉字符串 str 左侧的空格|
|RTRIM(str) |去掉字符串 str 行尾的空格|
|REPEAT(str,x) |返回 str 重复 x 次的结果|
|REPLACE(str,a,b) |用字符串 b 替换字符串 str 中所有出现的字符串 a|
|STRCMP(s1,s2)| 比较字符串 s1 和 s2|
|TRIM(str) |去掉字符串行尾和行头的空格|
|SUBSTRING(str,x,y)| 返回从字符串 str x 位置起 y 个字符长度的字串|


