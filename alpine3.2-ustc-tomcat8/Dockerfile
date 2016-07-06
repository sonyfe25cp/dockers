FROM alpine3.2-ustc-java:8
MAINTAINER sonyfe25cp

# Install tomcat8
#RUN curl -Ls http://apache.fayea.com/tomcat/tomcat-8/v8.0.32/bin/apache-tomcat-8.0.32.tar.gz | tar -xzf - -C /opt 
WORKDIR /opt

RUN  wget -O tomcat8.tar.gz http://ftp.wayne.edu/apache/tomcat/tomcat-8/v8.0.36/bin/apache-tomcat-8.0.36.tar.gz && mkdir tomcat8 && tar -xzf tomcat8.tar.gz -C tomcat8 --strip-components 1 && rm tomcat8.tar.gz


EXPOSE 8080


#RUN pwd

CMD ["/opt/tomcat8/bin/catalina.sh", "run"]

