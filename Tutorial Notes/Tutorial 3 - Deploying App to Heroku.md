# Tutorial 3 - Deploying App to Heroku
### Setup Heroku App
Initialize a git repository with `$ git init`.

Update ```server.js```:
```javascript
const http = require('http');

const server = http.createServer((req, res) => {
    res.end('This is my first response');
});

server.listen(process.env.PORT || 3000);
```
Adding `process.env.PORT` allows heroku to allocate their port.

Add and commit changes:
```
$ git add .
$ git commit -m "Initialized project"
```

Install the Heroku CLI [here](https://devcenter.heroku.com/articles/heroku-cli).

Create ```Procfile``` file in the root directory with `$ touch Procfile`.

Update ```Procfile```:
```
web: node server.js
```
Login to heroku with `$ heroku login`.

Create a heroku app with `$ heroku create [app-name]`.

Push your changes to the heroku repository with `$ git push heroku master`.

Visit the app via the link provided in the console apon completing the build.

You should see the text `This is my first response`.
