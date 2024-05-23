FROM golang:1.22
ENV WORKDIR /build
WORKDIR $WORKDIR
COPY . .
RUN docker/build.sh
ENTRYPOINT /usr/local/bin/backboard
