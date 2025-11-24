FROM nginx:latest

COPY nginx-default.conf /etc/nginx/conf.d/default.conf

COPY ./quest-angular/browser /usr/share/nginx/html

CMD [ "nginx", "-g", "daemon off;" ]

EXPOSE 80
