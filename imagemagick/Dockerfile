FROM debian:sid
MAINTAINER Jessica Frazelle <jess@docker.com>

RUN apt-get update && apt-get install -y \
	imagemagick \
	--no-install-recommends \
	&& rm -rf /var/lib/apt/lists/*

CMD [ "imagemagick" ]
