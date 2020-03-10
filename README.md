# 01-getting-started

This directory contains the source code from the tutorial.

# mount local volume to container
docker run -p XX:YY -v source:destination <image-name>

docker run -p 8083:80 -v ~/cicd/docker/Ytube_JakeWright/01mount_volume/src:/var/www/html ytube-jakewright

Source: [Watch Learn Docker in 12 Minutes](https://youtu.be/YFl2mCHdv24)
