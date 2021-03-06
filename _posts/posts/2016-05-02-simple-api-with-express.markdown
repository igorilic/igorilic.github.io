---
layout: post
title: Simple Api With Express
modified:
categories: blog
excerpt:
tags: []
image:
  feature:
date: 2016-05-02T13:44:13+02:00
---

If you're want to build an Api in javascript, ExpressJs is a right thing to do so.
You can use this Api for various clients building the Api in a smart and productive way. 

## Prerequisites

- node with npm
- (optional) gulp

## Base server

We are going to need some kind of server. Express is great for server setup, because it's so simple to implement.
Before we beginning to code our server, we need to setup the project. So let's go to the console/ terminal in folder of choice and type
    npm init 
With this we are going to create package.json with init data. 

Now, go to the console and install express.
    npm install --save express 
Don't forget "--save" so you can save information on package and version in your package.json.

Now we can configure server. I name the file app.js, but you can go with whatever you want, index.js or something else.

    var express = require('express');
    var app = express();
    // port
    var port = process.env.PORT || 3000;
    // server
    app.listen(port, function() {
        console.log('Server is up and running at port ' + port);
    });

## REST

REST is abbreviation for the Representational State Transfer. 
It is the set of constraints or rules how you communicate with the service. 

## Gulp setup

First you have to have installed gulp globally. If you haven't one, just do so with:

    npm install --global gulp

If you are doing this on Mac or Linux, maybe you will have to this with 

    sudo npm install --global gulp

