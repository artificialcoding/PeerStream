Multi-Client WebRTC Scalable Broadcast
======================================

## Usage

The signaling server uses Node.js and `ws` and can be started as 
follows:

```
$ npm install
$ npm start
```

With the server running, open Chrome and go to to `https://[server]` from any client.

Optionally, use a URL parameter to specify the client display name, e.g. `https://[server]/?displayName=Boston`

You may have conflicting tasks already using the default HTTP and/or 
HTTPS ports (80 and 443), which will result in an error on startup. 
Change the constants in server.js and go to 

https://localhost:[HTTPS_PORT]

##
Steps to start-->

1) Run npm install OR npm install --save ws in the terminal opened in PeerStream Directory.

IF RUNNING ON LAN
2) Uncomment line 75 and replace the IP by your IP. Also comment the line 76.
  
                            OR  
  
IF EXPOSING APP TO INTERNET -- ngrok can be used for making our local webApp public ::
2) Just install ngrok and go to the directory where it is installed and run -->  ./ngrok http https://localhost:8443
 
3) Run npm start in the terminal opened in PeerStream Directory

```
