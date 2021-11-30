# Chibisafe-Sharex-Scraper

Simple Script written in Python for download galleries of images / videos

# Supported links:

- <https://cyberdrop.me/>
- <https://bunkr.is/>
- <https://pixl.is/>
- <https://putme.ga/>

# Installation

You will need to install [git](https://git-scm.com/), and then run `git clone [repository url]`
from your terminal/cmd.

To run this, you will also need [python](https://www.python.org/), if you will be installing
from windows, also don't forget to check Add to PATH box during the installation!

After that, you will need to install the needed python packages. To do that, run
`pip3 install -r requirements.txt` (if that won't work, you can also try
`python3 -m pip install ...`)

# Run Script

To run python script, just type the following command
`python3 main.py -u <url>`

# Command usage

`-u` **Required** - The url which contains images or videos. Supported links: `pixl.is`, `cyberdrop.me`, `putme.ga`, `bunkr.is`

`-p` **Optional** -  Show progress bar from each url. By default it's False

`-w` **Optional** - Maximum amount of workers for downloading. By default it's 20 which is usually fast enough

By default displays the progress bar for downloaded files.

# Notes

Note that the script maintains an event log `logs.log` that can be used to understand system activity and diagnose problems.





