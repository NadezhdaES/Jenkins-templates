FROM ubuntu:18.04
RUN apt-get update && \
    apt-get install --no-install-recommends -y gcc && \
    apt-get clean && rm -rf /var/lib/apt/lists/*
    apt-get install wget busybox-extras netcat-openbsd python py-pip bash && \
    pip install awscli
CMD tail -f /dev/null

