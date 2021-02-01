FROM centos:7
#MAINTAINER wenxinlee2015
ADD ./goserver-todo /root/
RUN chmod +x /root/goserver-todo
RUN yum install -y net-tools
WORKDIR /root/
CMD [ "/root/goserver-todo" ]
