FROM ubuntu:18.04
RUN apt-get update && \
    apt-get install --no-install-recommends -y gcc && \
    apt-get clean && rm -rf /var/lib/apt/lists/*
    apk add --no-cache curl wget busybox-extras netcat-openbsd python py-pip bash && \
    pip install awscli
RUN apk --purge -v del py-pip
CMD tail -f /dev/null
CMD tail -f /dev/null

