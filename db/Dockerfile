FROM postgres:12.3-alpine

COPY 001_data.sql /docker-entrypoint-initdb.d/001_data.sql

ENV PGDATA=/data