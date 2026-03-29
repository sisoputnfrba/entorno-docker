FROM ubuntu:22.04

ENV DEBIAN_FRONTEND=noninteractive

RUN apt-get update -y && apt-get install -y software-properties-common

RUN add-apt-repository -y ppa:git-core/ppa

RUN apt-get install -y \
    libbison-dev \
    libcunit1-dev \
    libevent-dev \
    libfl-dev \
    libfuse-dev \
    libncurses5-dev \
    libreadline-dev \
    libssl-dev \
    autotools-dev \
    build-essential \
    cmake \
    ninja-build \
    pkg-config \
    g++ \
    gcc \
    gdb \
    ltrace \
    make \
    strace \
    valgrind \
    curl \
    git-all \
    htop \
    ssh \
    net-tools \
    neofetch \
    tar \
    unzip \
    7zip \
    tig \
    tree \
    wget \
    xclip \
    hexedit \
    nano \
    vim \
    emacs \
    sudo \
    && apt-get remove -y unattended-upgrades \
    && rm -rf /var/lib/apt/lists/*
