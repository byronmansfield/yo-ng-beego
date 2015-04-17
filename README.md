# An Angular-Beego Yeoman Generator

This is a fork from [ninnemana's](https://github.com/ninnemana/generator-angular-beego) Angular-Beego Yeoman Generator

## Installation

You will need the following installed and set up

* [Git](http://git-scm.com)
* [node.js](http://nodejs.org)
* [Go](http://golang.org/)

Then with node you can install Yeoman:

    `npm install -g yo`

Then you can install the yo-ng-beego generator:

    `npm install -g generator-angular-beego`

## Creating a Beego service

In a new directory, generate the service:

    `yo angular-beego`

    note: right now just use the original version, I will update once I have a version I am happy with and turn it into a generator

Get the dependencies:

    `go get`

Run the service:

  Terminal 1
    `grunt server`

  Terminal 2
    `bee run`

Your service will run at [http://localhost:8080](http://localhost:8080).

The Grunt server supports hot reloading of client-side HTML/CSS/Javascript file changes.

## Other

For more on this repo, about, wishlist, etc please check out the [wiki](https://github.com/byronmansfield/yo-ng-beego/wiki)
