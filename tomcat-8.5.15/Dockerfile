FROM tomcat:8.5.15-alpine

LABEL maintainer "tyzl931019@gmail.com"

COPY tomcat-users.xml /usr/local/tomcat/conf/tomcat-users.xml

RUN rm -rf /usr/local/tomcat/webapps

EXPOSE 8080
EXPOSE 1099
