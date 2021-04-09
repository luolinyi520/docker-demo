# 依赖java8的jdk镜像
FROM openjdk:8

# 镜像作者信息
MAINTAINER lyluo<lyluo@sunisco.com>

# 解压复制到容器里面
ADD /app/docker-demo-0.0.1-SNAPSHOT.jar app.jar

# 暴露8080端口
EXPOSE 8080

# 启动项目要执行的命令
ENTRYPOINT ["java", "-jar", "/app.jar"]
