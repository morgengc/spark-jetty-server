Windows下操作步骤:

1. 设置环境变量SPARK_HOME=F:\Scala\spark-1.6.0-bin-hadoop2.6, ./pom.xml中引用了该环境变量
2. 修改./pom.xml，将软件版本调整为我使用的版本
3. 在该目录下mvn clean install
4. 进入war目录mvn jetty:run
5. 访问http://localhost:8080/test

本机因为内存不够大，没能运行成功，但jetty确实启动了。

