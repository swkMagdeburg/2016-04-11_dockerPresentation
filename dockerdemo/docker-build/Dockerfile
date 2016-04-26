FROM java:8-jre
MAINTAINER Tobias Blaschke <blaschke@eudemonia-solutions.de>

COPY ./TobiDocker /docker

RUN mkdir /data && chmod +x /docker/bin/TobiDocker
EXPOSE 8080
CMD ["/docker/bin/TobiDocker", "server", "/docker/bin/config.yml"]
