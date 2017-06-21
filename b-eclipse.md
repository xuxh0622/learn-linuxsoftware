##### 下载地址 

> [https://www.eclipse.org/downloads](https://www.eclipse.org/downloads)

##### 准备工作

```bash
[java@** /]$ cd /usr/alice/java
[java@** /]$ tar -zxvf eclipse-jee-neon-3-linux-gtk-x86_64.tar.gz  #解压目录，x从文档中提取文件，v处理文件列表，z通过gzip解压，f使用档名
[**@** /]$ cp -r eclipse /usr/alice/java  #复制解压后的目录，r循环复制整个目录文件
```

##### 安装软件

```bash
[**@** /]$ cd /usr/alice/java/eclipse  #到当前地址
[**@** /]$ ./eclipse  #正常打开安装完成，出错jdk没有配置
[**@** /]$ ln -s /usr/alice/java/eclipse/eclipse /home/xuxhm/Desktop/eclipse  #创建桌面链接方式
```







