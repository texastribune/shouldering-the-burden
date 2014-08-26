# Shouldering the Burden

Shouldering the Burden (renamed to Bypassed by the Miracle) is a weeklong series of stories about people who have been left out of the economic growth of the Texas Miracle. This part of the story, *No Miracle Here*, is a series of vignettes about these people.

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


## Maps
To create the maps, use [https://github.com/duner/d3_texas_pins](https://github.com/duner/d3_texas_pins) and the NYTimes's [SVG Crowbar](http://nytimes.github.io/svg-crowbar/). I ended up using ImageMagik to convert the SVGs to PNGs so that they'd work on more browsers.
