FROM mysql:5.7
RUN usermod -u 1000 mysql
RUN apt-get update
RUN apt-get install vim -y
RUN mkdir -p /var/run/mysqld && \
  chmod -R 777 /var/run/mysqld
