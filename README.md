This repo contains more development on an earlier sketch found here: https://github.com/davidptracy/phoneGyroToMotor

To use the code you must be running two separate servers; a nodeWS server on your arduino Yun and a node socket.io server on your remote/local host.

There are two client files. Master.html streams camera data back to the cellphone and client.html rsends out gyrometer data to the arduino.
