# rpi-sickrage

Dockerfile to set up a SickRate container, based on the Hypriot image

## Build

    docker build --tag qnm/rpi-sickrage git://github.com/qnm/rpi-sickrage.git

## Run

    docker run -d -p 8081:8081 -v <LOCAL_MOVIES_FOLDER>:/movies --restart=always --name sickrage qnm/rpi-sickrage


