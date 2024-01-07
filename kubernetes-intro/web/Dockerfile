# syntax=docker/dockerfile:1

FROM ubuntu:22.04
WORKDIR /app
RUN chown -R 1001 /app
USER 1001
EXPOSE 8000
CMD python /app/app.py