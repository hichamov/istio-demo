FROM nginx:latest
RUN apt-get update -y
RUN apt-get install net-tools netcat telnet iputils-ping -y
ADD index.html /usr/share/nginx/html
EXPOSE 80
STOPSIGNAL SIGTERM
CMD ["nginx", "-g", "daemon off;"]