# syntax=docker/dockerfile:1
FROM varnish:7.6

LABEL maintainer="Irontree Inc. <gebara68@gmail.com>" \
      org.label-schema.name="irontreecms-varnish" \
      org.label-schema.description="Irontree CMS Platform Varnish image." \
      org.label-schema.vendor="Irontree Inc."

COPY etc/varnish.vcl /etc/varnish/default.vcl
