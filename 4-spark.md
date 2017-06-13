##### 下载地址

> [http://spark.apache.org/downloads.html](http://spark.apache.org/downloads.html]([http://spark.apache.org/downloads.html](http://spark.apache.org/downloads.html))
>
> [http://mirrors.hust.edu.cn/apache/spark/spark-2.1.1/spark-2.1.1-bin-hadoop2.7.tgz]([http://mirrors.hust.edu.cn/apache/spark/spark-2.1.1/spark-2.1.1-bin-hadoop2.7.tgz])

##### 安装

```bash
[java@** /]$ su java  #切换到java用户
[java@** /]$ tar -zxvf spark-2.1.1-bin-hadoop2.7.tgz  #解压目录，x从文档中提取文件，v处理文件列表，z通过gzip解压，f使用档名
[**@** /]$ cp -r spark-2.1.1-bin-hadoop2.7 /usr/alice/java  #复制解压后的目录，r循环复制整个目录文件
[java@** /]$ cd /usr/alice/java
```
