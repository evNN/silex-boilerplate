Silex Boilerplate
=================

This is a simple boilerplate for an application written with the [Silex PHP 
microframework](http://silex.sensiolabs.org/). It is intended to be a starting 
point for a REST Web application.  It comes with Twig, MongoDB, and LESS support by 
default.

## Installation ##
Installation is very easy. It makes use of [Composer](http://getcomposer.org/) 
for PHP as well as git submodules for dependencies not yet available as a 
Composer package. Open up a new Terminal window and run this command:

``` bash
curl -S https://raw.github.com/evNN/silex-boilerplate/master/system/get.sh | sh
```

This will create a new directory `silex-boilerplate` in the current working directory
and install all dependencies for the project.

If you have PHP 5.4 installed, you can simply run the following and start a new
local development server to test out your app:

``` php
php -S localhost:8080 ./silex-boilerplate
```

## Future ##
I intend to integrate this fully with [Backbone Boilerplate](https://github.com/tbranyen/backbone-boilerplate)
as a backend/REST portion of the framework.
