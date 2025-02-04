FROM ubuntu:24.04 AS base

RUN apt-get update -y && \
    apt-get install -y --no-install-recommends \
    apt-transport-https \
    bash \
    ca-certificates \
    curl \
    git \
    git-lfs \
    gnupg-agent \
    jq \
    openssh-client \
    perl \
    python3 \
    python3-pip \
    python3-dev \
    python3-crcmod \
    lsb-release \
    rsync \
    software-properties-common \
    tini \
    sudo \
    gnupg \
    zip \
    unzip \
    build-essential

COPY hooks/* /base/hooks/
