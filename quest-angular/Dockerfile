FROM nginx:latest

WORKDIR /app

COPY nginx-default.conf /etc/nginx/conf.d/default.conf

COPY /app/quest-angular/browser /usr/share/nginx/html

CMD [ "nginx", "-g", "daemon off;" ]

EXPOSE 80
