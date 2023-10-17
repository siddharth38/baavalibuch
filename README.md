<h1 align="center">
🌐 Assignment of baavalibuch
</h1>
<p align="center">
MongoDB, Expressjs, React, socket.io
</p>

This is a fullstack implementation in MongoDB, Expressjs, React, socket.io ,multer.

## clone or download
```terminal
$ git clone 
$ npm i
```
Run client and server runs concurrently in different terminal session, in order to make them talk to each other
## Check points of the Assignment
1. Created a backend tier using ExpressJS.
2. Created a PWA using React that that accepts text input (ID), a photo, text input (friendID) and password, and sends it to the backend. Also UI changes on interaction
3. The backend server should has -
a. Add the persons ID (A) to mongodb database
b. Add the friendID (B) to the friend list in the person
c. store the encrypted photo in a directory on the disc using multer (A)
d. update friend's (B) friendList to include person (A)
e. Implement auth so that A and B can't see each other's friends
4. Calculate the connectedness of the social graph
5. Messaging between person A and B
6. Created a new repo and commited all changes.


## project structure
```terminal
back/
   package.json
ui-frontend/
   package.json
...
```
## Prerequisites
- [MongoDB](https://gist.github.com/nrollr/9f523ae17ecdbb50311980503409aeb3)
- [Node](https://nodejs.org/en/download/) 
- [npm](https://nodejs.org/en/download/package-manager/)


## Client-side usage(PORT: 3000)
```terminal
$ cd ui-frontend  
$  npm i   
$ npm start      

// deployment for client app
$ npm run build 
$ npm run start 
```

## Server-side usage(PORT: 3001)

```terminal
// in the root level
$ cd back
$ echo "DATABASE=YOUR_MONGODB_URL_STRING" >> src/.env
```

### Start

```terminal
$ cd back 
$ npm i       
$ npm start
```


### After creating heroku


## BUGs or comments

Email Me: siddharth.kumar28717@gmail.com 

## Author
Siddharth Kumar


