# A basic apache server. To use either add or bind mount content under /var/www
FROM ubuntu:latest

RUN apt-get update && apt-get install -y apache2 && apt-get clean && rm -rf /var/lib/apt/lists/*

EXPOSE 8080

CMD ["/usr/sbin/apache2", "-D", "FOREGROUND"]
