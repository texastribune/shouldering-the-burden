# Shouldering the Burden

TODO: What's the project about?

## Setup

The builder depends on both [Grunt](http://gruntjs.com/) and [http://bower.io/](http://bower.io/), which both depend on [Node.js](http://nodejs.org/). If you do not have these installed, you'll need to get them.

Node.js comes first – we recommend using [Homebrew](http://brew.sh/) if you are a OS X creature (which we all are, for now). This should play well with Windows, but documenting that setup process is not a priority.

`brew update && install node`

Once Node.js is installed, you'll use [npm](https://www.npmjs.org/) – the Node.js package manager – to install Grunt and Bower globally.

`npm install -g grunt-cli bower`

Once those are in, you're ready to start installing the builder's dependencies.

From the template's root directory:

`npm install && bower install`

And away you go!
