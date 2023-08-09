FROM alpine:3.16

COPY bin /app/bin
RUN chmod +x /app/bin/entrypoint.sh

ENTRYPOINT [ "/app/bin/entrypoint.sh" ]