
复制目录

构建镜像
docker build ./ -t mytomcat

运行镜像
docker run -d -p 8899:8080 -p 2000:1099 -v webapps:/usr/local/tomcat/webapps  mytomcat

注意可以修改tomcat-user.xml里面的密码
注意端口占用