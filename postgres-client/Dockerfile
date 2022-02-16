FROM alpine:3.15.0

ARG POSTGRES_VERSION=14.2-r0
RUN apk add --no-cache bash postgresql14-client=$POSTGRES_VERSION

CMD ["/bin/sh", "-c", "trap : TERM INT; sleep 9999999999d & wait"]