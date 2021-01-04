FROM alpine:edge
RUN apk --no-cache add alpine-sdk go
RUN adduser -D -G abuild -g "Alpine Package Builder" -s /bin/ash abuild
USER abuild
