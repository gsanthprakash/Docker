FROM almalinux:8 
RUN yum install nginx -y
RUN echo "hello, Welcom to Docker file a way of creating own images" > /usr/share/nginx/html/hello.html
CMD [ "nginx", "-g" "deamon off" ]
# deamon off command makes our container running and attached to screen