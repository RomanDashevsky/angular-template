FROM node:10.15.3-stretch

RUN mkdir -p /var/www/cli
WORKDIR /var/www/cli

RUN npm install -g @angular/cli

COPY ./entrypoint.sh /entrypoint.sh

EXPOSE 3000

ENTRYPOINT ["/entrypoint.sh"]