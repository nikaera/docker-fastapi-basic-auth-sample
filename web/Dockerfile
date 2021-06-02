FROM nginx:alpine

RUN apk add --update apache2-utils && \
    rm -rf /var/cache/apk/*

CMD htpasswd -Bbn -C 12 ${USER:?undefined} ${PASS:?undefined} > /etc/nginx/.htpasswd && \
    nginx -g "daemon off;"
