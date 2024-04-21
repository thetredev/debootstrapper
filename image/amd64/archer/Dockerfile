FROM archlinux:base

ENV LC_ALL=C

RUN pacman -Syy \
    && pacman --needed --noconfirm -S arch-install-scripts \
    && pacman -Scc
