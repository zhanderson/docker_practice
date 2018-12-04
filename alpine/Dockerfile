FROM alpine
RUN apk update \
    && apk add curl
ENTRYPOINT [ "curl", "-s", "https://ip.cn" ]