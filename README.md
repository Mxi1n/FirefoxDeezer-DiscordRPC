# FirefoxDeezer-RPC

![example](https://media.discordapp.net/attachments/1129846289937469490/1138878834335293560/image.png?width=849&height=150)

Discord music rich presence status with **support for album covers**. Written in JavaScript.

**Only Linux is supported.**

> **⚠️ Notice:** It's in pre-alpha state of development and may not work properly. Expect bugs, errors etc.

## Supported players
Any player or app with [MPRIS](https://wiki.archlinux.org/title/MPRIS) support, also including both Google Chrome and Firefox.

## Requirements
To work, it needs the [playerctl](https://github.com/altdesktop/playerctl) package installed. On it's github page you can find instructions on how to install it for your distribution, but it should be available in the  repositories of the majority of distributions.

## Installation
Download the executable from the [Releases](https://github.com/patryk-ku/node-music-discord-rpc/releases) page.

Then simply execute the `node-music-discord-rpc` file. **For now script will crash without Discord running in the background.** This will be fixed later so you will be able to launch it at the system start-up but it's not ready yet.

## System usage

As this is written in JavaScript and run using node.js you might think that the system usage might be very high for such a simple script, but actually it's not. Depending on what you consider too high, of course. It uses about **78 MiB** of ram and CPU load of my *powerful* i5-4460 is around **0.2%** every 15 seconds while it's updating status.


## Running from source

Dependencies: node.js and npm installed.
Clone the repository and run:

```
npm install
```

```
node app.js
```