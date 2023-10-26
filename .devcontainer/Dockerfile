#
# Copyright © 2023 inpyjama.com. All Rights Reserved.
# Author: Piyush Itankar <piyush@inpyjama.com>
#

FROM mcr.microsoft.com/vscode/devcontainers/base:ubuntu

ENV DEBIAN_FRONTEND=noninteractive

RUN sudo apt-get update
RUN sudo apt-get install --no-install-recommends -y \
  ca-certificates \
  sudo \
  gdb-multiarch \
  gcc-riscv64-unknown-elf \
  binutils-common \
  make \
  curl \
  git-core \
  wget \
  vim \
  nano \
  ssh \
  tree \
  less \
  build-essential \
  python3 \
  python3-dev \
  python3-pip \
  binutils \
  make \
  binutils-riscv64-linux-gnu \
  qemu-system-riscv32 \
  gcc-arm-linux-gnueabihf \
  libc6-dev-armhf-cross \ 
  qemu-user-static \
  libc6-dev-arm64-cross \
  gcc-aarch64-linux-gnu \
  g++-arm-linux-gnueabihf \
  libstdc++-4.8-dev-armhf-cross \
  g++-aarch64-linux-gnu \
  libstdc++-4.8-dev-arm64-cross \
  zsh \
  xxd \
  strace \
  man

RUN yes | unminimize

# terminal colors with xterm
ENV TERM xterm
