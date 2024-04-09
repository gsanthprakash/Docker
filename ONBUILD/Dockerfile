FROM almalinux:8
RUN yum instdall nginx -y
RUN rm -rf /usr/hsare/nginx/html/index.html
ONBUILD ADD index.html /usr/share/nginx/html/index.html
RUN echo "hello, Wlecome to Docker. A way to creating won images" > /usr/share/nginx/html/hello.html
CMD [ "nginx", "-g", "deamon off;"]