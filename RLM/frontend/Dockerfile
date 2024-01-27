FROM nginx
COPY  /rivers-level-monitor /usr/share/nginx/html
COPY default.conf /etc/nginx/conf.d/default.conf
ENTRYPOINT [ "nginx", "-g", "daemon off;" ]