##### 下载地址

> [http://www.scala-lang.org/download/](http://www.scala-lang.org/download/)

##### 安装

```bash
[java@** /]$ su java  #切换到java用户
[java@** /]$ tar -zxvf scala-2.12.2.tgz  #解压目录，x从文档中提取文件，v处理文件列表，z通过gzip解压，f使用档名
[**@** /]$ cp -r scala-2.12.2 /usr/alice/java  #复制解压后的目录，r循环复制整个目录文件
[java@** /]$ cd /usr/alice/java
[java@** /]$ vim /etc/profile  #在后面添加如下配置
export PATH=/usr/local/scala-2.12.2/bin:$PATH
[**@** /]$ source /etc/profile  #重新加载配置文件
```

##### 检测

```bash
[**@** /]$ scala  #有提示安装成功
```

