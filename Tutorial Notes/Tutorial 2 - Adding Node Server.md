# Tutorial 2 - Adding Node Server
### Create Node Server
Create the file ```server.js``` in the root directory:
```
$ touch server.js
```
This server can be run with ```$ node server.js```.

Update ```server.js```:
```javascript
const http = require('http');

const server = http.createServer((req, res) => {
    res.end('This is my first response');
});

server.listen(3000);
```
Update ```package.json```:
```json
...
"scripts": {
    "ng": "ng",
    "start": "npm ",
    "start": "ng serve",
    "build": "ng build",
    "test": "ng test",
    "lint": "ng lint",
    "e2e": "ng e2e"
  },
...
```
