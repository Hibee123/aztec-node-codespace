FROM ubuntu:22.04

# Install basic tools and Docker
RUN apt-get update && apt-get upgrade -y && \
    apt-get install -y curl iptables build-essential git wget lz4 jq make gcc nano automake autoconf tmux htop nvme-cli libgbm1 pkg-config libssl-dev libleveldb-dev tar clang bsdmainutils ncdu unzip libleveldb-dev docker.io

# Optional: Install Aztec CLI
RUN bash -c "$(curl -s https://install.aztec.network)"
