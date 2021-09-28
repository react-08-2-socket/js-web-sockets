# Web Sockets

## Task 1.
Please, implement an ability for the application to work with WebSocket Server (client side).
Implement this in client.js file. Do not make changes in index.html.
User should be able to enter his nickname and message, and after a click on the 'Send' button, the information should be sent to WebSocket Server in the form *nickname: message*
The application should also display messages, received from WebSocket Server in the chat element. Each massage should be displayed in a new line

## Task 2.
Please, implement work of ws WebSocket Server in server/index.js. 
WebSocket Server should run on 8082 port and keep track of its connected clients (use built-in ability).
Message, received from one of the clients should be sent to all of them. (Simple implementation of chat.)