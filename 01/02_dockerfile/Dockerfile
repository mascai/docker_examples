# Mandatory line, specify image
FROM ubuntu

MAINTAINER DKA DEVELOP <alekmosk25@gmail.com>

# Script in the image
RUN apt-get update && apt-get install cowsay -y && ln -s /usr/games/cowsay /usr/bin/cowsay

# Application to start in the image
ENTRYPOINT ["cowsay"]

