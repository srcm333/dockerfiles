FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rm /usr/share/nginx/html/*
ONBUILD COPY src/ /usr/share/nginx/html/
CMD ["nginx", "-g", "daemon off"]
