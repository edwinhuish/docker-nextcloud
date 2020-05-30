FROM wonderfall/nextclouda:latest

RUN sed -i 's/dl-cdn.alpinelinux.org/mirrors.aliyun.com/g' /etc/apk/repositories \
    && apk update \
    && apk add ffmpeg \
       ghostscript \
    && rm -rf /var/cache/apk/* /tmp/* /root/.gnupg