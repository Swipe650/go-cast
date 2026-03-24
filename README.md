# go-cast

A command line tool to control Google Chromecast devices.

## Installation

Download the latest binaries from:
https://github.com/swipe650/go-cast/releases/latest

    $ sudo mv cast-linux-amd64 /usr/local/bin/cast-linux-amd64
    $ sudo chmod +x /usr/local/bin/cast-linux-amd64

## Usage

	$ cast-linux-amd64 help

Play a media file:

	$ cast-linux-amd64 --name Hifi media play http://url/file.mp3

Stop playback:

	$ cast-linux-amd64 --name Hifi media stop

Set volume:

	$ cast-linux-amd64 --name Hifi volume 0.5
	$ cast-linux-amd64 -name 'Hifi' mute
	$ cast-linux-amd64 -name 'Hifi' unmute

Close app on the Chromecast:

	$ cast-linux-amd64 --name Hifi quit

## Credits

Based on go library port by [ninjasphere](https://github.com/ninjasphere/node-cast)
