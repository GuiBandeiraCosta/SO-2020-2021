Communication system between clients and server using sockets

Functions:
- create command: c name type
- lookup command: l name 
- delete command: d name
- print tree state command: p outputfile
types:
- directory: d
- file: f

client: ./tecnicofs-client inputFile nomeserver
server : ./tecnicofs numthread nomeserver