FROM ubuntu:latest
RUN apt-get update && DEBIAN_FRONTEND=noninteractive apt-get install -y \
		vim \
		git \
		curl \
		wget \
		whois \
		genisoimage \
		cloud-image-utils \
	&& rm -rf /var/lib/apt/lists/*
