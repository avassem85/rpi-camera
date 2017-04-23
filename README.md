# rpi-camera

# Setup
- Install Hypriot https://blog.hypriot.com/ (don't forget to configure wifi network)

- Run RPi_Cam docker
'''bash
 docker run -d --name=rpi-cam2 -p=80:80/tcp --volume=/opt/vc:/opt/vc --device=/dev/vchiq --device=/dev/vcsm droogmic/rpi-cam-web
'''
