FROM debian:latest
LABEL maintainer="Chakshu Jain"
RUN apt update && apt install -y iputils-ping
ENTRYPOINT ["/bin/ping"]
CMD ["www.docker.com"]
