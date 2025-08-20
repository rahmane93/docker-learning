FROM ubuntu:16.04

RUN apt-get update && apt-get install -y nginx curl

EXPOSE 80

# Bon chemin !
WORKDIR /var/www/html

# On remplace l'index.html par ton sample.html
COPY index.html /var/www/html/index.html

CMD ["nginx", "-g", "daemon off;"]