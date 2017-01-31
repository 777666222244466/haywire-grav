# Haywire getgrav theme

Haywire is a modern starter theme for [getgrav](https://getgrav.org/). The idea behind the theme is to help developers to get started quickly on their new getgrav projects using modern frameworks and tools such as [yarn](https://yarnpkg.com/), [laravel-elixir](https://laravel.com/docs/5.3/elixir), [bootstrap](https://github.com/twbs/bootstrap-sass).

![screenshot](https://github.com/robbinfellow/haywire-grav/blob/master/screenshot.png?raw=true)

_Inspired by [Sage](https://roots.io/sage/) starter theme for wordpress by [roots](https://roots.io/)._

## Features

* Yarn
* Bootstrap-sass
* Laravel-elixir
* Gulp
* Bower

## Installation / Usage

### bin/gpm
        
        $ cd ~/gravroot
        $ bin/gpm install haywire
        $ cd /user/themes/haywire
        $ yarn
        $ bower install
        $ gulp


### Manual
        
        $ cd ~/gravroot/user/themes
        $ git clone https://github.com/robbinfellow/haywire-grav.git haywire
        $ cd haywire
        $ yarn
        $ bower install
        $ gulp


_The `templates/default.html.twig` is setup to display the latest subpages of your @home page as blogposts._

### Gulp

Compile assets => `gulp`

Watch scss/js => `gulp watch`

Minify assets => `gulp --production`

**Note:** _(compiled assets goes into the /dist directory)_

### Yarn

Install package => `yarn add packagename --save-dev`

Remove package => `yarn remove packagename --save-dev`

## Useful links

* [yarn](https://yarnpkg.com/en/docs/)
* [bootstrap-sass](https://github.com/twbs/bootstrap-sass)
* [gulp](http://gulpjs.com/)
* [laravel-elixir](https://laravel.com/docs/5.3/elixir)
* [getgrav](https://learn.getgrav.org/)
* [bower](https://bower.io/)
