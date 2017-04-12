# alexa-app-example

An example Alexa Skill project using the [alexa-app](https://github.com/alexa-js/alexa-app) module with Express.

## Deploying locally

Make sure you have [Node.js](http://nodejs.org/) and the [Heroku Toolbelt](https://toolbelt.heroku.com/) installed.

```sh
git clone git@github.com:alexa-js/alexa-app-example.git # or clone your own fork
cd alexa-app-example
npm install
npm start
```

Your app should now be running on *[http://localhost:8080](http://localhost:8080)*.

### Testing it

You can access a test page to verify if the basic setup is working fine: *[http://localhost:8080/test](http://localhost:8080/test)*.

## Deploying to Heroku

```sh
heroku create
git push heroku master
heroku open
```

Alternatively, you can deploy your own copy of the app using this button:

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy?template=https://github.com/alexa-js/alexa-app-example)

Your app should now be running on *https://`<app-name>`.herokuapp.com*, where `<app-name>` is the heroku app name.

### Testing it

You can access a test page to verify if the basic setup is working fine: *https://`<app-name>`.herokuapp.com/test*.