FROM node:8.16.0-alpine
WORKDIR /usr/src/app

RUN apt-get update && apt-get install -y --no-install-recommends \
    wget \
    cpio \
    sudo \
    git \
    zip \
    unzip \
    curl \
    xterm \
    vim \
    lsb-release && \
    rm -rf /var/lib/apt/lists/*


