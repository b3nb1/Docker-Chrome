### Google Chrome in a Docker container
* ```git clone``` this repository
* ```docker build -t chromecontainer .```
* ```docker run -p 5900:5900 -e VNC_SERVER_PASSWORD=password --user apps --privileged chromecontainer```
