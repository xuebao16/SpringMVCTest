# SpringMVC 示例项目

这是一个简单的SpringMVC示例项目,展示了基本的Spring Boot和SpringMVC的使用。

## 项目结构

项目的主要结构如下:

## 如何启动项目

要启动这个SpringMVC示例项目,请按照以下步骤操作:

1. 确保您的系统中已安装Java开发环境(JDK)和Maven。

2. 在项目根目录下打开命令行终端。

3. 执行以下Maven命令来构建项目:

   ```
   mvn clean package
   ```

4. 构建成功后,使用以下命令启动应用:

   ```
   java -jar target/demo-0.0.1-SNAPSHOT.jar
   ```

5. 应用启动后,打开浏览器并访问 http://localhost:8080

   您应该能看到"Hello, SpringMVC!"的欢迎信息。

注意: 默认情况下,应用将在8080端口上运行。如果该端口已被占用,您可以在application.properties文件中修改server.port属性来更改端口号。
