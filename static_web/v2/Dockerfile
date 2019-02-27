# Version: 0.2
FROM ubuntu:14.04
MAINTAINER ilki-company "contact@ilki.fr"
RUN apt-get update && apt-get install -y nginx
RUN echo 'Bonjour, je suis votre conteneur' > /usr/share/nginx/html/index.html
CMD ["/bin/bash"]
EXPOSE 80