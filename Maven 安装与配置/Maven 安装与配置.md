# Maven 安装与配置

1. 下载 Binary zip archive：[Download Apache Maven](https://maven.apache.org/download.cgi)

2. 配置环境变量：

   1. MAVEN_HOME: D:\maven
   2. %MAVEN_HOME%\bin
   3. 命令行界面运行 mvn -v

3. 配置本地仓库默认位置：

   ```xml
   <!-- D:\Maven\conf\settings.xml -->
   <localRepository>D:/Maven/repository</localRepository>
   ```

4. 配置镜像网站：

   ```xml
   <!-- D:\Maven\conf\settings.xml -->
   <mirror>
     <id>alimaven</id>
     <name>aliyun maven</name>
     <url>http://maven.aliyun.com/nexus/content/groups.public/</url>
   </mirror>
   ```