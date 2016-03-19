FROM alpine3.2-ustc-java:8
MAINTAINER sonyfe25cp

# Install tomcat8
RUN curl -Ls http://apache.fayea.com/tomcat/tomcat-8/v8.0.32/bin/apache-tomcat-8.0.32.tar.gz | tar -xzf - -C /opt 

EXPOSE 8080

RUN ln -s /opt/apache-tomcat-8.0.32 /opt/tomcat8

WORKDIR /opt/tomcat8


RUN pwd

CMD ["bin/catalina.sh", "run"]

