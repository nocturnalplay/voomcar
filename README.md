# Hand Gesture Server

## web socket server

> currently this is a single threaded webSocket server only serves if the client conneted to the web socket server

## download or clone the project

```
git clone https://github.com/nocturnalplay/handgesture_processing_server.git
```

## Install the required packages for this project

```
cd handgesture_processing_server
sudo apt install python3-pip
sudo pip install -r requirements.txt
```

## Server configuration Details in serverData

- STREAMING_SERVER_URL = "" // url of the video streaming device
- HOST = "" //configure server name
- PORT = "" //and port

## start the project

```
python3 start.py
```
