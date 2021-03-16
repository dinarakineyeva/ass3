FROM alpine
RUN apk update
RUN apk add mysql mysql-client
WORKDIR /opt
COPY import.sh /opt
COPY mydatabase.sql /opt
CMD ./import.sh
