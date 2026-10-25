FROM ubuntu:24.04

WORKDIR /usr/src/app

COPY script.sh .

RUN apt update && apt install -y curl && \
    chmod +x script.sh

CMD ["./script.sh"]