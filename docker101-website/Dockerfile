FROM nginx:latest

COPY index.html /usr/share/nginx/html
COPY ./img /usr/share/nginx/html/img/

EXPOSE 80 443 	

CMD ["nginx", "-g", "daemon off;"]