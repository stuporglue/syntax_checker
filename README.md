Syntax Checker
==============

A one-stop-shop for all your syntax checking needs. 

This script wraps multiple syntax checking programs into one convenient bash script 
so you can always run the same command to syntax check your files regardless of 
what type they are.

What's Supported?
----------------
The following formats are currently supported, and require the following programs 
to be installed to work.

 * css -- csslint -- https://github.com/CSSLint/csslint
 * html -- tidy
 * js/json  -- hint
 * php -- php for command line
 * python -- pylint or python
 * ruby -- ruby 
 * bash -- bash
 * xml -- xmllint
 * sql (postgres specifically) -- pgsanity
 * git/jpg/png/svg -- identify (imagemagick)

Installing for OSX
------------------
### CSS

 # Install [NPM](https://www.npmjs.com/)
 # Install csslint

    sudo npm install -g csslint

### Images (gif,jpg,p ng,svg)

ImageMagick recommends using [MacPorts](http://www.macports.org/) or [Homebrew](http://brew.sh/) to install

### HTML 

 # Download [Cmake](http://www.cmake.org/download/)
 # Clone tidy and build it

    git clone https://github.com/htacg/tidy-html5.git
    cd tidy-html5/build/cmake
    cmake ../..
    make
    sudo make install

### JavaScript / JSON

 # Install [NPM](https://www.npmjs.com/)
 # Install jshint
    sudo npm install -g jshint

### PHP

    PHP comes bundled with OSX since 10.0.0

### Python

    sudo easy_install pylint

### Ruby

    Ruby comes installed on OSX

### Bash

    Bash comes installed on OSX

### XML

    xmllint comes installed on OSX? 

### PostgreSQL SQL Files

    sudo easy_install pgsanity

### Text Files (mime type checking only)

    /file/ comes installed on OSX
