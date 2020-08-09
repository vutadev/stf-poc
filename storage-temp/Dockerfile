FROM vutadev/stf-arm64:latest

USER root
RUN mkdir data && chown stf:stf data
USER stf
VOLUME ["data"]
