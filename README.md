# Overview
| Front End    | Back End      |
| -------------|:-------------:|
| Angular.js   | Node.js       |
|              | Express       |
|              | MongoDB       |

# Node.js
### Install
https://nodejs.org/en/
```bash
sudo apt install nodejs -y

# Check install
$ node -v
$ npm -v
```

# Express

# Angular
### Install (Angular CLI)
https://cli.angular.io/
```bash
# install cli
$ npm install -g @angular/cli
```
### Setup Project
```
# create project
$ ng new [app name]
$ cd [app name]

# run developmental server
$ ng serve

# exit server with ctrl + c
```
You can view the project at http://localhost:4200/
### VSCode Extensions
Download the "Angular Essentials" extension from the VS Marketplace
# MongoDB
dsf

# Github


# Heroku
### Install
https://devcenter.heroku.com/articles/heroku-cli

### Setup App
Create ```Procfile``` file in the lowest directory with contents:
```
web: npm start
```

```bash
# login to heroku
$ heroku login

# create a heroku app
$ heroku create [app name]

# push changes to heroku repository
$ git push heroku master
```
