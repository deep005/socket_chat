Websocket 101 - In this project I have tried to make a real time chat service using socket.io and node.

The app allows multiple clients to connect to one server and communicate via sockets in realtime. The messages sent by
one client is forwarded to all active connections including the sender.

The app shows an intuitive message of which client is typing a message currently to all the
active connections except the sender by making use of the broadcast property.

At this point of time the app is not storing the messages in a database so the future connections wont be able to see
the messages shared before they joined the chat.
