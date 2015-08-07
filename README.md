docker-vlc
===========

This is a docker project for build and run vlc video translation and recording


How it's work
===========

1. Download project:

    ``$ git clone https://vukor@github.com/vukor/docker-vlc.git ~/docker``

2. Install docker, docker-compose in your system

3. If your system is CentOS 6.x run:

    `` $cd .vlc && ln -s Dockerfile-CentOS-6 Dockerfile ``

4. If your system is CentOS 7.x run:

    `` $cd .vlc && ln -s Dockerfile-CentOS-7 Dockerfile ``

5. Setup your scripts or vlm-configurations, edit docker-compose.yaml and run:

    `` $docker-compose up -d  ``


share dirs
===========

``etc - configs files``

``rec - recording files``

``logs - vlc logs``

