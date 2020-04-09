# **nginx-lua-prometheus**

https://github.com/knyar/nginx-lua-prometheus

https://github.com/openresty/lua-nginx-module

先去Lua的官网（http://www.lua.org/ftp/）下载最新发布包：

http://www.lua.org/ftp/

```bash
[root@ip-172-16-81-146 ~]# wget http://www.lua.org/ftp/lua-5.3.5.tar.gz
[root@ip-172-16-81-146 ~]# tar -xzvf lua-5.3.5.tar.gz
```

安装openresty

```bash
sudo yum install yum-utils
sudo yum-config-manager --add-repo https://openresty.org/package/centos/openresty.repo
sudo yum-config-manager --add-repo https://openresty.org/package/amazon/openresty.repo
sudo yum install openresty
```

[ec2-user@ip-172-16-82-136 ~]$ sudo yum install yum-utils











