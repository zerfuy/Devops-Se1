FROM postgres:11.6-alpine

ENV POSTGRES_DB=db POSTGRES_USER=root POSTGRES_PASSWORD=root

ADD CreateSchema.sql /docker-entrypoint-initdb.d
ADD InsertData.sql /docker-entrypoint-initdb.d
