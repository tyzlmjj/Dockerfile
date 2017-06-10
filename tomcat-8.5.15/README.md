# Tomcat 

1. 构建镜像

```shell
docker build ./ -t mytomcat
```

2. 运行镜像

```shell
docker run -d -p 9000:8080 -p 2000:1099 -v .../webapps:/usr/local/tomcat/webapps mytomcat
```

**注意**
- 可以修改tomcat-user.xml里面的密码
- 端口占用问题
- 挂载webapps目录一定要绝对路径
