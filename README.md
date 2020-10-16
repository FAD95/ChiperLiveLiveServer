# Description

This server works as a encoder and as a endpoint for live video transmissions, the general idea of the server is take that video in real time and apply a serie of transformations to stream that it in the best way to a RTMP server.

# Tecnologies

## WebSockets (Socket.io)

Through WebSockets the video and the audio is received in real time. 

## ffmpeg

Trough ffmpeg that video received is processed and transformed with a serie of parameters that define how is gonna be sended. 


# Run Scripts

*  `npm install` Install dependencies
*  `npm run start` Run the server in prouction mode
*  `npm run dev` Run the server in development mode





