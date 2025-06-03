---
abbrlink: 1238062248
author: Allen
hidden: true
published: 2023-08-26 17:51:01
title: flarum使用
tags: ['服务器']
---


```
# 安装fileinfo扩展  假设为php8.0 
cd /root/lnmp1.9/src & tar -xvf php-8.0.20.tar.bz2 
cd /root/lnmp1.9/src/php-8.0.20/ext/fileinfo

/usr/local/php/bin/phpize
./configure --with-php-config=/usr/local/php/bin/php-config
make && make install


\usr\local\php\etc\php.ini
disable_functions = passthru,exec,system,chroot,chgrp,chown,shell_exec,popen,ini_alter,ini_restore,dl,openlog,syslog,readlink,symlink,popepassthru,stream_socket_server

#末尾添加
extension=fileinfo.so
extension=exif.so

```



```
php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"
php -r "if (hash_file('sha384', 'composer-setup.php') === 'e21205b207c3ff031906575712edab6f13eb0b361f2085f1f1237b7126d785e826a450292b6cfd1d64d92e6563bbde02') { echo 'Installer verified'; } else { echo 'Installer corrupt'; unlink('composer-setup.php'); } echo PHP_EOL;"
php composer-setup.php
php -r "unlink('composer-setup.php');"

mv composer.phar /usr/local/bin/composer



cd /home/wwwroot/flarum & composer update

```




```
# 添加重写
/usr/local/nginx/conf/rewrite/other.conf

/home/wwwroot/flarum/.nginx.conf

```
```
# Pass requests that don't refer directly to files in the filesystem to index.php
location / {
try_files $uri $uri/ /index.php?$query_string;
}

# Uncomment the following lines if you are not using a `public` directory
# to prevent sensitive resources from being exposed.
# location ~* ^/(\.git|composer\.(json|lock)|auth\.json|config\.php|flarum|storage|vendor) {
# deny all;
# return 404;
# }

# The following directives are based on best practices from H5BP Nginx Server Configs
# https://github.com/h5bp/server-configs-nginx

# Expire rules for static content
location ~* \.(?:manifest|appcache|html?|xml|json)$ {
add_header Cache-Control "max-age=0";
}

location ~* \.(?:rss|atom)$ {
add_header Cache-Control "max-age=3600";
}

location ~* \.(?:jpg|jpeg|gif|png|ico|cur|gz|svg|mp4|ogg|ogv|webm|htc)$ {
add_header Cache-Control "max-age=2592000";
access_log off;
}

location ~* \.(?:css|js)$ {
add_header Cache-Control "max-age=31536000";
access_log off;
}

location ~* \.(?:ttf|ttc|otf|eot|woff|woff2)$ {
add_header Cache-Control "max-age=2592000";
access_log off;
}

# Gzip compression
gzip on;
gzip_comp_level 5;
gzip_min_length 256;
gzip_proxied any;
gzip_vary on;
gzip_types
application/atom+xml
application/javascript
application/json
application/ld+json
application/manifest+json
application/rss+xml
application/vnd.geo+json
application/vnd.ms-fontobject
application/x-font-ttf
application/x-web-app-manifest+json
application/xhtml+xml
application/xml
font/opentype
image/bmp
image/svg+xml
image/x-icon
text/cache-manifest
text/css
text/javascript
text/plain
text/vcard
text/vnd.rim.location.xloc
text/vtt
text/x-component
text/x-cross-domain-policy;

```
```
#如果数据库连不上  先导入创建Allen这个用户
mysql -u root -p Allen < /Allen.sql

```