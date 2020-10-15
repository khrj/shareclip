# Shareclip

Shareclip shares your clipboard across multiple devices. Copy on your phone and paste on your desktop!

Thanks to:
- [Ishan Goel](https://github.com/quackduck/), this is a node.js rewrite of [uniclip](https://github.com/quackduck/uniclip)
- [Aaryan Porwal](https://github.com/aaryanporwal), this was his idea originally

## Quickstart

Requires [node.js](https://nodejs.org/en/) to be installed.
Run:

```
npx shareclip
```

## Downloads

Note: If you already have node.js installed (If you don't know what that is then probably not), then follow **Running** below instead of this.

Downloads are at [releases](https://github.com/KhushrajRathod/shareclip/releases)

Open your terminal, and run

```
shareclip-[os]
```

Didn't understand? Install [the latest node.js](https://nodejs.org/en/) and follow the instructions under **Running**

## Installing

Run
```
npm install -g shareclip
```

And then
```
shareclip
```

## Usage

After running `shareclip`, you should see something like:

```
RUNNING AS SERVER
WARNING: THE PANDAS ARE COMING
Listening on port 54979
Run "shareclip http://192.168.29.128:54979" on a different device
```

> **WARNING: THE PANDAS ARE COMING**

Run the command provided (Here, it's `shareclip http://192.168.29.128:54979`) on another device where you have shareclip installed and enter. Your clipboard should be shared automatically between your devices now. Note that your devices must be under the same WiFi network.

## Specific instructions for Android

- [Download termux](https://play.google.com/store/apps/details?id=com.termux)
- Run   
```
apt update -y && apt install termux-api nodejs -y
```

- Follow instructions under **Running**
