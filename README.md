# Description

This server works as a encoder and as a endpoint for live video transmissions, the general idea of the server is take that video in real time and apply a serie of transformations to stream that video in the best way to a RTMP server.

# Tecnologies

## WebSockets (Socket.io)

Through WebSockets the video and the audio is received in real time. 

## ffmpeg

Trough ffmpeg that video received is processed and transformed with a serie of parameters that define how is gonna be sended. 


# Run Scripts

*  `mpm install` Install dependencies
*  `mpm run start` Run the server in prouction mode
*  `mpm run dev` Run the server in development mode





