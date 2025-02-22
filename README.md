# Websocket Server

Chat websocket server build with node js

To run the project use these docker command inside the project root directory

<br>

> **Run the server**

Clone the project

```
git clone https://github.com/henriqueoz/websocket-chat-server.git
```

Run inside the project folder

```
docker build -t websocket-server .
docker run -d --rm -p <port>:3000 --name websocket-server-container websocket-server

```

<br>

> **Optional for logging**

Run inside project folder

```
docker logs -f websocket-server-container 1> logs/logs.log &

```

<br>

Chat client app in flutter: https://github.com/henriqueoz/websocket-chat-app

Chat client terminal: https://github.com/henriqueoz/websocket-chat-client
