# Chat App
Tech Stack - React.js , Node.js , Express.js , Socket.io , MongoDB , Tailwind.css

Created a chat App using MERN stack and used Socket.io library for real-time bi-directional communication between different users.

## How to run the Project
There are 2 folders Server and Client.

I have not included the node_modules in this repository so you have to install them.

1. For Client node_modules -
```
cd client
npm install
```

2. For Server node_modules -
```
cd server
npm install
```

3. After that you have to put mongoDB connection string link in server .env file
```
server > .env > CONNECTDB
```

4. Now start the Server -
```
cd server
npm start
```
  or if you have nodemon installed
```
cd server
nodemon index.js
```

5. Now start the Frontend i.e. Client -
```
cd client
npm run dev
```

> Note - Client and Server both needs to be running concurrently

Now open any browser and go to this link - http://localhost:5173/

> Note - I have not made this Project responsive
