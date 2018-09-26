FROM node:8-alpine

RUN npm install -g s3rver \
  && mkdir -p /tmp/s3

ENTRYPOINT [ "/usr/local/bin/s3rver", "-d", "/tmp/s3", "-h", "0.0.0.0" ]
