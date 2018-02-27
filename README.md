# Twitter Bootstrap subtheme for drupal 7

## Installation

**rename theme folder and move into**

`$ mv drupal-bootstrap-subtheme less && cd less`

**download Bootstrap source code**

`$ wget https://github.com/twbs/bootstrap/archive/v3.3.7.zip`

`$ unzip v3.3.7.zip && mv bootstrap-3.3.7 bootstrap`

`$ rm v3.3.7.zip`

**install Grunt via npm**

`$ npm install`

## Compile less and uglify js @ filesave

> see gruntfile.js and less.info

**run Grunt watch**

`$ grunt watch`
