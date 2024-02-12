
# Project Title

Real time collaborative tree editor

# Tech 
NodeJS + ReactJS + MySQL

# Client-side 
Change location to client
```bash
cd ./client
```
Install all dependencies
```bash
npm i 
```
run client-side
```bash
npm start
```

# Server-side
Change location to client
```bash
cd ./server
```
Install all dependencies
```bash
npm i 
```
Create database and table in mysql for that use existing query given in 
```bash
path : server/db.script
```

Find .env.sample file and create new .env file at same location
```bash
path : server/.env.sample
```

run client-side
```bash
npm run server
```

Whenever a user makes changes to a node or adds nodes, the client application sends the updates to the server, which then updates the MySQL database. The server notifies other clients in real-time about these changes throught socket. That's how real time tree editor works.
