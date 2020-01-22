FROM ubuntu
MAINTAINER PRAJUL CHAUHAN:prajul.chauhan2000@gmail.com
RUN apt-get update
RUN apt-get install nodejs -y
RUN apt-get install npm -y
#CMD ["ln -s /usr/bin/nodejs /usr/bin/node"]
RUN npm install -g http-server
COPY ./index.html /usr/apps/hello-docker/index.html
WORKDIR /usr/apps/hello-docker/
ENTRYPOINT http-server -s
