# GitChatApp
GitChatApp is a chat application that requires users to login through GitHub.

[![logo](./public/images/gitchatapp.png)](./public/images/gitchatapp.png)

## Application Architecture
Node.js, Express, EJS, MongoDB, Socket.IO, jQuery

GitChatApp uses Node.js and Express for server-side rendering and to facilitate GitHub OAuth. Server-side rendering is done with the help of EJS. GitChatApp uses a MongoDB database to store each user. The only information stored in the database is the username. GitChatApp uses Socket.IO and jQuery to send messages from the user to the server. The server then emits the messages to all the users in real-time. GitChatApp is currently deployed on Heroku: https://git-chat-app.herokuapp.com/

## Dependencies
babel-env, babel-register, cors, dotenv, ejs, express, jquery, mongoose, morgan, socket.io, superagent, supertest

## License
MIT License