##### 下载地址

> [http://www.oracle.com/technetwork/java/javase/downloads/index.html](http://www.oracle.com/technetwork/java/javase/downloads/index.html)

##### 准备工作

```bash
[**@** /]$ groupadd java  
[**@** /]$ useradd -g java java  #g为当前用户分用户组
[**@** /]$ passwd java  #分配密码
[**@** /]$ su java
[**@** /]$ cd /usr/alice
[**@** /]$ mkdir java  #创建java目录
[**@** /]$ chown java.java java  #当前目录用户和组分配
[**@** /]$ tar -zxvf jdk-8u131-linux-x64.tar.gz  #解压目录，x从文档中提取文件，v处理文件列表，z通过gzip解压，f使用档名
[**@** /]$ cp -r jdk-8u131-linux-x64 /usr/alice/java  #复制解压后的目录，r循环复制整个目录文件
```

##### 安装软件

```bash
[**@** /]$ vim /etc/profile  #最文档最后配置环境，readonly文档命令模式:q !sudo tee %进行保存
#set java environment
JAVA_HOME=/usr/java/jdk1.8.0_131
CLASSPATH=$JAVA_HOME/lib/
PATH=$PATH:$JAVA_HOME/bin
export PATH JAVA_HOME CLASSPATH
[**@** /]$ source /etc/profile
```

##### 测试安装情况

```bash
[**@** /]$ echo $JAVA_HOME  #通过输出查看安装是否成功
[**@** /]$ echo $CLASSPATH
[**@** /]$ echo $PATH
[**@** /]$ java -version
```





