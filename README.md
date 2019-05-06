# Deep Reinforcement Learning for Simulated Self Driving Car

## Steps for simulation
Make sure you have all files installed before you start the simulation
To start the simulation run the Simulation file. 
Obstacle or road can be created using right click of the mouse.
To save the training data, press save button on the graphical interface.
Press load button to load the last saved training data.

# Installation Instructions for Ubuntu

I've used Ubuntu 16.04 - Compatible mostly with Ubuntu all versions

Copy the commands into the termainal and paste it to setup the environment.
```console
    sudo apt-get install -y \
    python-pip \
    build-essential \
    git \
    python \
    python-dev \
    ffmpeg \
    libsdl2-dev \
    libsdl2-image-dev \
    libsdl2-mixer-dev \
    libsdl2-ttf-dev \
    libportmidi-dev \
    libswscale-dev \
    libavformat-dev \
    libavcodec-dev \
    zlib1g-dev

sudo apt-get install -y \ 
    libgstreamer1.0 \
    gstreamer1.0-plugins-base \
    gstreamer1.0-plugins-good

## Pytorch
sudo pip install http://download.pytorch.org/whl/cpu/torch-0.3.1-cp27-cp27mu-linux_x86_64.whl

## pip
sudo pip install --upgrade pip

## Kivy
sudo apt-get install python-kivy

## Python plotting
sudo pip install matplotlib

sudo apt-get install python-tk

## Spyder
sudo apt-get install spyder
```
# Installation Instructions for Windows

## Anaconda 
https://www.continuum.io/downloads

Download the right installer of python 3.6 (64-bit if you are on a 64-bit machine and 32-bit if you are on a 32-bit machine)

## Kivy
https://www.dropbox.com/s/wso12fmfd55ysus/Kivy-1.10.1.dev0-cp36-cp36m-win_amd64.whl?dl=0

Then , Open Anaconda Prompt as Admin
once the Anaconda Prompt is open, type in these commands in the order specified
Enter y to proceed when prompted.

1. conda install -c anaconda python=3.6.1
2. conda install -c peterjc123 pytorch=0.1.12

 Change the directory in the Anaconda Prompt to the known path where the kivy wheel was downloaded. 
 So change the below command accordingly for your system
 cd C:\Users\user_name\Downloads <- (user_name - replace your pc user_name) 
 
Once the path has been changed succesfully, you should now enter these commands in the Anaconda prompt to install Kivy

1. pip install docutils pygments pypiwin32 kivy.deps.sdl2 kivy.deps.glew
2. pip install kivy.deps.gstreamer
3. pip install Kivy-1.10.1.dev0-cp36-cp36m-win_amd64.whl

