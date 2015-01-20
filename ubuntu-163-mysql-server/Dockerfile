FROM docker.cn/docker/mysql:5.6
RUN cp /etc/apt/sources.list   /etc/apt/sources.list-bak
RUN echo  'deb http://mirrors.163.com/ubuntu/ trusty main restricted universe multiverse' > /etc/apt/sources.list
RUN echo  'deb http://mirrors.163.com/ubuntu/ trusty-security main restricted universe multiverse' >> /etc/apt/sources.list
RUN echo  'deb http://mirrors.163.com/ubuntu/ trusty-updates main restricted universe multiverse' >> /etc/apt/sources.list
RUN echo  'deb http://mirrors.163.com/ubuntu/ trusty-proposed main restricted universe multiverse' >> /etc/apt/sources.list
RUN echo  'deb http://mirrors.163.com/ubuntu/ trusty-backports main restricted universe multiverse' >> /etc/apt/sources.list
RUN echo  'deb-src http://mirrors.163.com/ubuntu/ trusty main restricted universe multiverse' >> /etc/apt/sources.list
RUN echo  'deb-src http://mirrors.163.com/ubuntu/ trusty-security main restricted universe multiverse' >> /etc/apt/sources.list
RUN echo  'deb-src http://mirrors.163.com/ubuntu/ trusty-updates main restricted universe multiverse' >> /etc/apt/sources.list
RUN echo  'deb-src http://mirrors.163.com/ubuntu/ trusty-proposed main restricted universe multiverse' >> /etc/apt/sources.list
RUN echo  'deb-src http://mirrors.163.com/ubuntu/ trusty-backports main restricted universe multiverse' >> /etc/apt/sources.list
COPY my.cnf /etc/mysql/my.cnf
EXPOSE 3306
