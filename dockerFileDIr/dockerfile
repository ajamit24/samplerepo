FROM devopsedu/webapp
Maintainer "aj"
ADD /tmp/gitRepo/website /var/www/html
RUN rm /var/www/html/index.html
EXPOSE 80
CMD ["/usr/sbin/apachectl", "-D", "FOREGROUND"]
