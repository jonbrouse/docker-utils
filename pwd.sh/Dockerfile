FROM alpine

RUN apk add --update gnupg bash ncurses && \
    rm -rf /var/cache/apk/*

COPY assets/pwd /opt/pwd

WORKDIR /opt/pwd

RUN chmod +x pwd.sh

ENTRYPOINT ["./pwd.sh"]
