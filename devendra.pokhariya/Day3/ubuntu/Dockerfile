FROM ubuntu:latest
LABEL Name="Dev Pokhariya"
RUN apt-get update && \
    apt-get install nodejs -y&& \
    apt-get install npm -y && \
    #ln -s /usr/bin/nodejs /usr/bin/node
RUN npm install -g http-server
COPY ./index.html /usr/apps/hello-docker/index.html
WORKDIR /usr/apps/hello-docker/
ENTRYPOINT [ "http-server", "-s" ]
