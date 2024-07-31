# 
🚀 `A free WebRTC browser-based video call, chat and screen sharing` 🚀

<br>






<br>


## Features

- Is `100% Free` and `Open Source`
- No download, plug-in or login required, entirely browser based
- Unlimited number of conference rooms without call time limitation
- Desktop and Mobile compatible
- Optimized Room Url Sharing (share it to your participants, wait them to join)
- WebCam Streaming (Front - Rear for mobile)
- Audio Streaming
- Screen Sharing to present documents, slides, and more...
- File Sharing, share any files to your participants in the room
- Select Audio Input - Output && Video source
- Recording your Screen, Audio and Video
- Chat with Emoji Picker & Private messages & Save the conversations
- Simple collaborative whiteboard for the teachers
- Full Screen Mode on mouse click on the Video element
- Possibility to Change UI Themes
- Right click on the Video elements for more options
- Direct `peer-to-peer` connection ensures lowest latency thanks to `webrtc`
- Supports `API` (Application Programming Interface)

## Demo

- `Open`https://video-conferecing-application.herokuapp.com/ 
- `Pick` your personal Room name and `Join To Room`
- `Allow` to use the camera and microphone
- `Share` the Room URL and `Wait` someone to join for video conference

## Quick start

- You will need to have [Node.js](https://nodejs.org/en/blog/release/v12.22.1/) installed, this project has been tested with Node version 12.X
- Clone this repo

```bash
git clone https://github.com/miroslavpejic85/mirotalk.git
cd mirotalk
```

## Setup Turn and Ngrok

- Copy .env.template to .env

```bash
cp .env.template .env
```

`Turn`

Not mandatory but recommended.

- Create an account on http://numb.viagenie.ca
- Get your Account USERNAME and PASSWORD
- Fill in your credentials in the `.env` file
- Set `TURN_ENABLED=true`, if you want enable the Turn Server.

`Ngrok`

Not mandatory at all, but useful for tests and debug.

- Get started for free https://ngrok.com/
- Fill in your authtoken in the `.env` file
- Set `NGROK_ENABLED=true`, if you want to expose the server using the https tunnel, starting it from your local PC.

## Install dependencies

```js
npm install
```

## Start the server

```js
npm start
```

- Open http://localhost:3000 in browser



If you want to use a client on another computer/network, make sure you publish your server on an `HTTPS` connection.
You can use a service like [ngrok](https://ngrok.com/) or deploy it on:

<br>

[![Deploy on Heroku](https://www.herokucdn.com/deploy/button.svg)](https://www.heroku.com/)
