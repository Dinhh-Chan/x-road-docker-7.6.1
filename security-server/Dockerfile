FROM niis/xroad-security-server-sidecar:7.6.1

ARG XROAD_TOKEN_PIN=123456xrd!
ARG XROAD_ADMIN_USER=xrd
ARG XROAD_ADMIN_PASSWORD=secret

RUN rm -f /etc/xroad/conf.d/local.ini
COPY local-config.ini /etc/xroad/conf.d/local.ini