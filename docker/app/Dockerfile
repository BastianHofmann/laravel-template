FROM joblocal/base-app:alpine-3.7

RUN apk add --update \
  php7-tokenizer \
  && rm -rf /var/cache/apk/*


WORKDIR /var/www
