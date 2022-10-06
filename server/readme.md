# Chatroom

TCP chat room, developed in Go.
## Executing

To build project, run:

```
go build .
```

To run the project, run:

```
./tcp-chat
```

Server is running on port 8888. To join with a client (using *telnet*):

```
telnet localhost 8888
```

## Modes

- /nick <nickname> -> change nickname
- /join <room_name> -> join room (creates on if one with same name does not exist)
- /rooms -> list available rooms
- /msg -> send msg to chat room
- /quit -> quit chat and close connection
