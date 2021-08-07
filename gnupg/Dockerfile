FROM alpine:3
RUN apk add --no-cache gnupg
LABEL io.whalebrew.name gpg
LABEL io.whalebrew.config.volumes '["~/.gnupg:/root/.gnupg"]'
ENTRYPOINT ["gpg"]
