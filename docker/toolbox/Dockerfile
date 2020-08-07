FROM alpine
RUN apk add --no-cache --update curl wget busybox-extras netcat-openbsd py-pip bash postgresql-client && \
pip install awscli
RUN apk --purge -v del py-pip
CMD tail -f /dev/null
