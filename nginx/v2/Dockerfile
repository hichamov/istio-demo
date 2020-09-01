FROM nginx:latest
ADD index.html /usr/share/nginx/html/
EXPOSE 80
STOPSIGNAL SIGTERM
CMD ["nginx", "-g", "daemon off;"]