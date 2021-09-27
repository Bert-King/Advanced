[Tomcat官网](http://tomcat.apache.org/)

[Ubuntu安装Tomcat的指导](https://www.cnblogs.com/peng-lan/p/10512824.html)

### Linux系统下查找Java路径

1. 先判断用户是否安装JDK:
> java -version

2. 如果用户设置了**JAVA_HOME**, 可以通过以下命令直接查找
> echo $JAVA_HOME

3. 模糊查找java位置
> which java 或者 whereis java

  3.1 查软链接
  > ls -l /usr/bin/java
 
 3.2 查JDK目录
 > ls -l /etc/alternatives/java
