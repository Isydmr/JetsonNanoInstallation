# Jetson Nano Installation Guide
Resources &amp; Commands for a proper Jetson Nano Installation 
## Swap & Basics 

```
git clone https://github.com/jkjung-avt/jetson_nano.git
cd jetson_nano/
./install_basics.sh
```
```
sudo fallocate -l 8G /mnt/8GB.swap
sudo mkswap /mnt/8GB.swap
sudo swapon /mnt/8GB.swap
```
## OpenCV
Refer to [this](https://jkjung-avt.github.io/opencv-on-nano/).
## Terminator
```
sudo apt-get update
sudo apt-get install terminator
```
## Nano (Text Editor)
```
sudo apt-get install nano
```
## Socket
```
sudo apt-get install socket
```
## Serial
```
sudo apt-get install python-serial python3-serial
```
## PyQT5
```
sudo apt-get install qttools5-dev-tools
sudo apt-get install python3-pyqt5
sudo apt-get install pyqt5-dev-tools
```
## Pygame
```
sudo apt-get install python-dev libsdl-image1.2-dev libsdl-mixer1.2-dev libsdl-ttf2.0-dev   libsdl1.2-dev libsmpeg-dev python-numpy subversion libportmidi-dev ffmpeg libswscale-dev libavformat-dev libavcodec-dev
pip3 install pygame
```
## Jetson Stats
```
sudo -H pip install -U jetson-stats
```
## Conda
https://sahilramani.com/2020/10/how-to-setup-python3-and-jupyter-notebook-on-jetson-nano/
## PortAudio
```
sudo apt-get install portaudio19-dev python-pyaudio python3-pyaudio
```
## VOSK-Api
pip install https://github.com/alphacep/vosk-api/releases/download/0.3.21/vosk-0.3.21-py3-none-linux_aarch64.whl

REBOOT!
------------------
##### References
<sub>[1] https://jkjung-avt.github.io/setting-up-nano/</sub> 
<sub> <br> </sub>
<sub>[2] https://stackoverflow.com/a/15368766/7977464 </sub> 

