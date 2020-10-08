[![Build Status](https://travis-ci.com/Hailot/dndtome-peerjs-server.svg?token=xT1ue64vcmex3JcsmvGC&branch=master)](https://travis-ci.com/Hailot/dndtome-peerjs-server)

# PeerServer: A server for PeerJS #

PeerServer helps establishing connections between PeerJS clients. Data is not proxied through the server.

### [https://peerjs.com](https://peerjs.com)

## Usage

### Run server
If you don't want to develop anything, just enter few commands below.

1. Install the dependencies:
    ```sh
    $ npm install 
    ```
2. Run the server:
    ```sh
    $ npm start
    ```
3. Check it: http://localhost:9000 It should returns JSON with name, description and website fields.

Also, you can use Docker image to run a new container:
```sh
$ docker run -p 9000:9000 -d peerjs/peerjs-server
```

