# FakeTerminal

A fake Javascript terminal for your website.

[Demo](http://hellopablo.github.io/faketerminal/)


## How to use

### Basic Usage

The easiest way to install faketerminal.js is via [Bower](http://bower.io).

    bower install faketerminal

Include the JS and the CSS in your page

    <!-- CSS -->
    <link href="/bower_components/faketerminal/dist/faketerminal.css" media="all" rel="stylesheet" type="text/css" />

    <!-- JS -->
    <script src="/bower_components/jquery/dist/jquery.min.js" type="text/javascript"></script>
    <script src="/bower_components/faketerminal/dist/faketerminal.min.js" type="text/javascript"></script>

Instantiate faketerminal on an empty `<div>`

    $('#myFaketerminal').faketerminal({
        options: '@todo'
    });


## Options

The following options are available to you:

[@todo]


## Adding Commands

Easily extend the basic set of commands which faketerminal responds to by ... [@todo]


## How to Contribute

I welcome contirbutions to fake terminal. Fork the repo and submit a pull request. Please ensure that faketerminal.js
compiles and that any relevant documentation is updated before sending the pull request.

### Compiling LESS and JS

I use Grunt to compile everything. Firstly, install `grunt-cli` globally. It's recommended to run the grunt client on a
per-project basis, so if you have it installed globally, remove it.

    npm install -g grunt-cli

Install the dev dependancies

    npm install

Call `grunt` in the project root

    grunt

If you wish to start the watcher, you can do so by calling:

    grunt autocompile

All the Less and JS files will be watched for changes, and compiled if necessary.