# SimpleExpressServer
Basic express server example
This example generated using express command. You must have express installed on your system

```sh
$ npm install express-generator -g
```

#Generated
```sh
$ express SimpleExpressServer
```


Assume node and npm (node package manager) is already installed

##Clone this repo

```sh
$ git clone https://github.com/adious/SimpleExpressServer.git
```

##Install install dependencies in package.json 

```sh
$ cd SimpleExpressServer
$ npm install
```

##Run server

```sh
$ npm start
```
##Run client in new terminal
```sh
$ curl http://localhost:3000
```

##Run client in browser
1. http://localhost:3000/
2. http://localhost:3000/users

##Response
If all goes well. you will see response msg back from server.

Server will output request information using morgan logger.

