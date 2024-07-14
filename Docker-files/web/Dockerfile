FROM nginx
LABEL "Project"="Vprofile-containers"
LABEL "Author"="Shay Guedj"

RUN rm -rf /etc/nginx/conf.d/default.conf
COPY nginvproapp.conf /etc/nginx/conf.d/vproapp.conf
