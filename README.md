# localFileServer
Create a local server for sharing files across devices connected over a network

## Set up
- Clone this repo: `https://github.com/ankitbhattab95/localFileServer.git`
- Move to the project dir: `cd localFileServer/code`
- Install dependencies: `npm i`
- Install pm2 globally: `npm i -g pm2`
- Start the pm2 process: `pm2 start pm2.json`

## Usage
- All the files inside `localFileServer/public` dir will be accessible to all the devices connected to the same network at [http://192.168.1.218:8080/](http://192.168.1.218:8080/)
- The port number may vary if 8080 is already in use. In such a case, check `pm2 logs` to find the port number of the server
