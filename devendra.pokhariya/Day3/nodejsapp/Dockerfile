FROM alpine:latest
LABEL NAME="Dev Pokahriya"
ENV dirpath=/app
RUN apk add --update nodejs npm
COPY ./ /app/
WORKDIR ${dirpath} 
CMD [ "node index.js" ]
