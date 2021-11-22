# Chibisafe-Sharex-Scraper

Simple Script written in Python for download galleries of images / videos

# Supported links:

* cyberdrop.me 
* bunkr.is 
* pixl.is 
* putme.ga

# Installation

If you already have Git installed, you can use `git clone`
1. You need to install the packages according to the configuration file with the following command `pip3 install -r requirements.txt`

> For Windows

Add Python to your PATH [Here](https://docs.python.org/3/using/windows.html)

# Run Script

To run python script, just type the following command

`python3 main -u <url>`

# Commands

`-u` **Required** - The url which contains images or videos. Supported links: pixl.is, cyberdrop.me, putme.ga, bunkr.is 
`-p` **Optional** -  Show progress bar from each url. By default its False

`-w` **Optional** - MAX_WORKERS. Define the maximum amount of workers for downloading. By default are 20 and its fast enough

By default displays the progress bar for downloaded files.

# Notes

Note that the script maintains an event log `logs.log` that can be used to understand system activity and diagnose problems.





