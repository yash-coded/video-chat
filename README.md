# Video Chat app with unique Room Id's 📢
A simple video chat app built with socket.io, expressjs, peerjs and webRTC protocol 📶
## Functionality 
- Creates a unique Room ID with uuid package #️⃣
- Multiple peers can join the room with this unique ID 👥
- Automatically remove the video stream when a peer is disconnected 📡

## Quick Setup
- Make sure to have nodejs installed on your machine.
- Install project dependancies with
``` bash
npm install
```
- Install nodemon globally
```bash
sudo npm install -g nodemon
```
- Run the project with:
```bash
nodemon server.js
```
### PeerJS Server setup
- Specifiy the port number in the new Peer instance:
``` JavaScript 
const myPeer = new Peer(undefined, {
  host: "/",
  port: "3001", //port number
});
```
- Run PeerJS server on your terminal on the specified port number:
```bash
peerjs --port 3001
```
## License
[MIT](https://choosealicense.com/licenses/mit/)
