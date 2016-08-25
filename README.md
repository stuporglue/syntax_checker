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
 * csv/tsv -- csvlint -- https://github.com/Clever/csvlint
 * html -- tidy -- https://github.com/htacg/tidy-html5
 * js/json  -- jshint -- https://github.com/jshint/jshint
 * php -- php for command line -- https://secure.php.net/
 * python -- pylint or python -- https://www.pylint.org/
 * ruby -- ruby -- https://www.ruby-lang.org/en/
 * bash -- bash -- https://www.gnu.org/software/bash/
 * xml -- xmllint -- http://xmlsoft.org/xmllint.html
 * sql (postgres specifically) -- pgsanity -- https://github.com/markdrago/pgsanity
 * git/jpg/png/svg -- identify (imagemagick) -- http://www.imagemagick.org/script/index.php
 * pem -- validate pem files (openssl) -- https://www.openssl.org/

Installing for OSX
------------------
### CSS

1. Install [NPM](https://www.npmjs.com/)
2. Install csslint

    sudo npm install -g csslint

### CSV/TSV

1. Install go
2. Install [csvlint](https://github.com/Clever/csvlint)

    go get github.com/Clever/csvlint/cmd/csvlint

### Images (gif,jpg,p ng,svg)

ImageMagick recommends using [MacPorts](http://www.macports.org/) or [Homebrew](http://brew.sh/) to install

### HTML 

1. You will need the [Developer Tools](https://developer.apple.com/xcode/) installed
2. Download [Cmake](http://www.cmake.org/download/) and install CMake.app in your Applications directory
3. Clone tidy and build it

     git clone https://github.com/htacg/tidy-html5.git
     cd tidy-html5/build/cmake
     /Applications/CMake.app/Contents/bin/cmake ../..
     make
     sudo make install

### JavaScript / JSON

1. Install [NPM](https://www.npmjs.com/)
2. Install jshint

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

    xmllint comes installed on OSX -- probably came with the developer tools

### PostgreSQL SQL Files

    sudo easy_install pgsanity

### Text Files (mime type checking only)

    file comes installed on OSX

### Openssl 

    openssl comes installed on OSX
