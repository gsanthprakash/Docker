FROM almalinux:8
RUN yum install nginx -y
RUN rm /usr/share/nginx/html/index.html
RUN echo "hello this is santh prakash" > /usr/share/nginx/html/index.html
ENTRYPOINT ["nginx", "-g", "deamon off;"]