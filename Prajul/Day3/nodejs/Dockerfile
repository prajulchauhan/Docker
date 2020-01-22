FROM alpine
MAINTAINER PRAJUL CHAUHAN:prajul.chauhan2000@gmail.com
RUN apk update
RUN apk add nodejs
COPY . /app
WORKDIR /app
CMD ["node index.js"]

