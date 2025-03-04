FROM alpine:edge

RUN addgroup -g 1000 node \
    && adduser -u 1000 -G node -s /bin/sh -D node

RUN apk update && apk upgrade --no-cache && \
    apk add --no-cache gcompat git go nodejs pnpm wasm-pack

