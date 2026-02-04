FROM mcr.microsoft.com/devcontainers/javascript-node:24-trixie

ENV DEBIAN_FRONTEND=noninteractive

RUN apt-get update \
  && apt-get install -y --no-install-recommends \
    build-essential \
    python3 \
    python3-pip \
    libvips-dev \
  && apt-get clean \
  && rm -rf /var/lib/apt/lists/*

WORKDIR /workspace
