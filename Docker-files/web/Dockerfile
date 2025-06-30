FROM nginx:1.29.0-alpine

LABEL "Project"="Vprofile"
LABEL "Author"="Imran"

RUN rm -rf /etc/nginx/conf.d/default.conf
COPY nginvproapp.conf /etc/nginx/conf.d/vproapp.conf