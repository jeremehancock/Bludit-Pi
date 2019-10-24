# Bludit-Pi
Raspberry Pi Setup for the [Bludit Flat File CMS](https://www.bludit.com/)

The goal of this project is to create an easy way to configure and install Bludit on a Raspberry Pi. 

> ####  *This build script should not be used on a Raspberry Pi that has previously had a webserver configured. This script will overwrite the "/var/www/html" directory!*

The following technologies are automatically installed for you.
* Apache
* PHP
* [Bludit](https://www.bludit.com/) (Latest Version)

## Pre-Installation
1. Raspberry Pi with [Raspbian](https://www.raspberrypi.org/downloads/raspbian/)
2. Git installed - `sudo apt-get install git`

## Installation Instructions
1. Find a directory on your Pi where you'd like to install this repo
2. Run `git clone https://github.com/mhancoc7/Bludit-Pi.git`
3. Run `cd Bludit-Pi`
4. Run `bash build.sh`

## Usage
1. Make sure the configuration process is completed
2. Point your web browser to http://raspberrypi.local (or whatever your Pi's hostname is set to) to view your Bludit site
3. Follow the steps to complete the Bludit installation

## Upgrade
* Run `bash build.sh`

> Keep in mind upgrading will remove any custom modifications that you have made to Bludit. It will not overwrite the content or settings that you have applied in the Bludit admin panel. 

## Note
If you receive an error message when loading Bludit in your web browser it could be that a step in the build process failed for some reason. It is safe to re-run the build.

## Disclaimer
All code is provided as-is without any warranty. Use at your own risk.
