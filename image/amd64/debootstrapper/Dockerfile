FROM ubuntu:22.04

ENV DEBIAN_FORNTEND=noninteractive \
    LC_ALL=C

RUN apt-get update \
    && apt-get install -y debootstrap \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/*
