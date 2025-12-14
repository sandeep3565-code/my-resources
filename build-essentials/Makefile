################################################################################
# File Name 	: Makefile
# Description	: Used to build essentials for all kinds of build
################################################################################

SHELL := /bin/bash

.PHONY: all targets

all: targets

targets:
	sudo apt update
	sudo apt install -y \
		git sudo vim bash-completion \
		tar zip unzip wget lsb-release \
		file xz-utils libssl-dev bzip2 \
		build-essential device-tree-compiler \
		bc u-boot-tools jq liblzo2-2 \
		cpio autoconf dosfstools rsync passwd
