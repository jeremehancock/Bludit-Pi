# Bludit-Pi
Raspberry Pi Setup for [Bludit Flat File CMS](https://www.bludit.com/)

The goal of this project is to create an easy way to configure and install Bludit on a Raspberry Pi. 

> `This build script should not be used on a Raspberry Pi that has previously had a webserver configured. This script will overwrite the "/var/www/html" directory!`

The following technologies are automatically installed for you:
* Apache
* PHP
* [Bludit v3.10.0 "Mateo"](https://www.bludit.com/)

## Pre-Installation
1. Raspberry Pi with [Raspbian](https://www.raspberrypi.org/downloads/raspbian/)
2. Git installed - `sudo apt-get install git`

## Installation Instructions
1. Find a directory on your Pi where you'd like to install this repo
2. Run `git clone git@github.com:mhancoc7/Bludit-Pi.git`
3. Run `cd Bludit-Pi`
4. Run `bash build.sh`

## Usage
1. Make sure the configuration process is completed and your virtual machine is ready
2. Point your web browser to http://raspberrypi.local to view your Bludit site
3. Follow the steps to complete the Bludit installation

> #### `Note: All code is provided as-is without any warranty. Use at your own risk.`
