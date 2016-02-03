FROM alpine

RUN apk add --update netcat-openbsd && \
    rm -rf /var/cache/apk/*

ENTRYPOINT ["nc"]
