# HES E8, Spring 2017 HW9: Node.js Web App

Node.js web app using the ESRI JS API and as follows:

* Live URL: https://e8-hw9.herokuapp.com/map
* Shows ESRI AGOL major US cities and freeway layers
* Developed using Node.js and Express web frameworks
* ESRI and Heroku templates used as referenced below

Details about the map and feature layers:

* Map is centered on San Francisco, CA
* City/freeway layers are added with FeatureLayer()

## References:

Web app was developed using these templates/tutorials:

* ESRI JS API, 2D Map Template: http://arcg.is/2nytHZt
* ESRI JS API, Layer Template: http://arcg.is/2nyNuIe
* ESRI AGOL, US Major Cities Layer: http://arcg.is/2nyyvht
* Heroku Node.js Tutorial: http://bit.ly/2nyFTJN

# Heroku Node.js Tutorial Instructions

A barebones Node.js app using [Express 4](http://expressjs.com/).

This application supports the [Getting Started with Node on Heroku](https://devcenter.heroku.com/articles/getting-started-with-nodejs) article - check it out.

## Running Locally

Make sure you have [Node.js](http://nodejs.org/) and the [Heroku Toolbelt](https://toolbelt.heroku.com/) installed.

```sh
$ git clone git@github.com:heroku/node-js-getting-started.git # or clone your own fork
$ cd node-js-getting-started
$ npm install
$ npm start
```

Your app should now be running on [localhost:5000](http://localhost:5000/).

## Deploying to Heroku

```
$ heroku create
$ git push heroku master
$ heroku open
```
or

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

## Heroku Documentation

For more information about using Node.js on Heroku, see these Dev Center articles:

- [Getting Started with Node.js on Heroku](https://devcenter.heroku.com/articles/getting-started-with-nodejs)
- [Heroku Node.js Support](https://devcenter.heroku.com/articles/nodejs-support)
- [Node.js on Heroku](https://devcenter.heroku.com/categories/nodejs)
- [Best Practices for Node.js Development](https://devcenter.heroku.com/articles/node-best-practices)
- [Using WebSockets on Heroku with Node.js](https://devcenter.heroku.com/articles/node-websockets)
