FROM devopsedu/webapp
RUN rm /var/www/html/*
ADD website /var/www/html
EXPOSE 80
CMD ["apachectl", "-D", "FOREGROUND"] 
