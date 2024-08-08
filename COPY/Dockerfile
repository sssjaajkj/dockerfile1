FROM almalinux:9
RUN dnf install nginx -y
# remove default content in the path
RUN rm -rf /usr/share/ngnx/html/index.html

COPY index.html /usr/share/ngnx/html/index.html

CMD [ "nginx", "-g","daemon off;"]