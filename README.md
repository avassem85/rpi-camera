# rpi-camera

# Setup
## Install Hypriot https://blog.hypriot.com/ 
- Create SD-card with Hypriot Docker Image for Raspberry Pi (https://blog.hypriot.com/downloads/)
- Configure WLAN (edit device-init.yaml)

## Run RPi_Cam docker
```bash
 docker run -d --name=rpi-cam2 -p=80:80/tcp --volume=/opt/vc:/opt/vc --device=/dev/vchiq --device=/dev/vcsm droogmic/rpi-cam-web
```

## Configure camera
Go to http://<IP>
Go to Camera Settings
Set Resolutions: Max View 972p 4:3
Set Flip: both
