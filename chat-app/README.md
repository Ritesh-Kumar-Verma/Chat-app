# Real time chat app 
Example of chat web application using Socket.IO with the MERN stack
Client in React, Server in Node.js/Express
On login user can set an avatar for the chat
All messages saved in MongoDB database
After user enters, they can see history of chats (10 last messages)



Install dependencies
-----
Go to each folder (client and server) and enter this to install dependencies

    $ yarn install
    
Have a .env file in the server folder with the following data
-----

    NODE_ENV=development
    SOCKET_PORT=5001
    HTTP_PORT=5002
    MONGODB_URL='<mongo db url>'
    CLOUDINARY_CLOUD_NAME='<cloudinary cloud name>'
    CLOUDINARY_API_KEY='<cloudinary api key>'
    CLOUDINARY_API_SECRET='<cloudinary secret key>'
    
Go to server folder and run in local development
-----

    $ yarn start-dev
    
Go to client folder and run in local development
-----

    $ yarn watch
