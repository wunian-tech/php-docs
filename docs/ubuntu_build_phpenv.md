## 基于Ubuntu16.04的Apache + Mysql + PHP7.0环境搭建

### 执行apt下载命令如下

* 安装前的更新 `sudo apt update`
* 安装apache2 `sudo apt install apache2` --> 打开浏览器输入 http:/localhost/
* 安装mysql `sudo apt-get install mysql-server` -> 执行 mysql -uroot -p 进入数据库 -> 执行sql语句查看mysql版本select version();
* 安装php7 `sudo apt install php7.0`
* 安装php7其他拓展 `sudo apt install libapache2-mod-php7.0 php7.0-mysql php7.0-curl php7.0-json`

### 根据情况修改/var/www/即apache根目录权限问题

* 设置apache根目录权限组 `sudo chown -R www-data:www-data /var/www/`
* 设置apache根目录文件权限 `sudo chmod -R 755 /var/www/`

### 安装其他拓展

* PHP bcmath module `sudo apt-get install php-bcmath`
* PHP gd `apt-get install php7.0-gd`

### OTHERS

* 材料仅供参考, 请你确定自己执行的每一行命令的明确意义

- [How to install PHP 7 in Ubuntu?](https://www.digitalocean.com/community/tutorials/how-to-upgrade-to-php-7-on-ubuntu-14-04)
- [How To Install Linux, Apache, MySQL, PHP (LAMP) stack on Ubuntu 16.04](https://www.digitalocean.com/community/tutorials/how-to-install-linux-apache-mysql-php-lamp-stack-on-ubuntu-16-04)
