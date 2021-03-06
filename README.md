This repository is a simple demo of Ember 1.1.2 and Ember Data 1.0.0-beta3 that features

* a `Creation` / `Read` / `Update` / `Delete` of a collection of `users`
* complex CSS transitions / animations on `views`
* Handlebars templates precompiling with [Grunt](http://gruntjs.com/getting-started)
* fully responsive UX (with touch events, and with animations between routes)


**Here's the demo ➔ [jkneb.github.io/ember-crud](http://jkneb.github.io/ember-crud)**

## Working with the files

### First install Grunt

[gruntjs.com/getting-started](http://gruntjs.com/getting-started) or `sudo npm install -g grunt-cli`

### Install the dev dependencies

First `cd` into the project and run `npm install`

This command will install locally the following node modules 

* [grunt](gruntjs.com)
* [grunt-contrib-sass](https://npmjs.org/package/grunt-contrib-sass)
* [grunt-contrib-concat](https://npmjs.org/package/grunt-contrib-concat)
* [grunt-contrib-watch](https://npmjs.org/package/grunt-contrib-watch)
* [grunt-ember-templates](https://npmjs.org/package/grunt-ember-templates)

### How to compile css

**Requirements:**  
Install Ruby ([RVM](https://rvm.io/rvm/install) is your friend), then `gem install sass`

Run the following command:  
`grunt watch` or `grunt sass`

### How to compile .hbs templates

Run the following command:  
`grunt watch` or `grunt emberTemplates`

### How to concatenate js files

Run the following command:  
`grunt watch` or `grunt concat`