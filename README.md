# harbor-box

harbor开箱即用,内置真实的SSL证书

## 前提

需要手动安装docker和dockercompose，请参考[CentOS7安装docker学习环境](https://www.jianshu.com/p/347b9a71d550)

* docker
  * Docker version 18.09.6, build 481bc77156
* docker-compose：
  * docker-compose version 1.24.1, build 4667896

## 安装harbor

```
git clone https://github.com/WALL-E/harbor-box.git
cd harbor-box
./prepare
./install.sh
```

## 使用

项目中使用了域名`harbor.docker-plus.xyz`，需要在host中把这个域名绑定到安装harbor的主机IP上，然后使用浏览器打开`https://harbor.docker-plus.xyz`即可
