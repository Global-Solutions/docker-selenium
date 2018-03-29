FROM selenium/node-chrome:3.11.0-bismuth
MAINTAINER Global Solutions co., ltd.

USER root
RUN apt-get update -qqy && apt-get install --no-install-recommends -y fonts-ipafont-gothic \
 && rm -rf /var/lib/apt/lists/* /var/cache/apt/*
USER seluser
