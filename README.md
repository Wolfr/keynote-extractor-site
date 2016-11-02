# keynote-extractor-site

[![Build Status](https://travis-ci.org/Dietr/hashi-boilerplate.svg?branch=master)](https://travis-ci.org/Dietr/hashi-boilerplate)

# Hashi boilerplate

Hashi boilerplate is an opinionated starter kit to help you build or prototype static marketing or content websites. It uses [Jekyll](http://jekyllrb.com/) as a static site generator, [Gulp](http://gulpjs.com/) as a worklow automation tool and a combination (Frankenstein build) of [InuitCSS](https://github.com/inuitcss)/[Chopstick](https://github.com/getchopstick) as CSS framework.

You are free to copy, modify, and distribute Hashi boilerplate, even for commercial purposes, without asking for permission. For any third-party code please refer to the corresponding license included in this project.

## How to use

### Dependencies

Hashi boilerplate needs the following tools to be installed properly:
- [Ruby](https://www.ruby-lang.org/en/) (v2.3.0) or [RVM](https://rvm.io/)
- [Bundler](https://bundler.io/)
- [Node.js](https://nodejs.org/en/) (v4.4.7) or [NVM](https://github.com/creationix/nvm)
- [Gulp](http://gulpjs.com/)

#### Install
To install run `bundle install && npm install`

#### Run
There are several options to run or build the site.

##### Using the Jekyll CLI

To run the Jekyll server use `jekyll serve`.
To build the Jekyll site use `jekyll build`.

##### Using the Gulp CLI
To run a [browser-sync](https://www.browsersync.io/) server and watch changes run `gulp watch`.

## Need help
Hashi boilerplate uses Jekyll to generate the html and process the `.scss` files. More information about these tools can be found on the following sites:
- [Jekyll documentation](http://jekyllrb.com/docs/home/)
- [Gulp documentation](https://github.com/gulpjs/gulp/blob/master/docs/getting-started.md)

Documentation of the '.scss' framework can be found as comments in the following files:
- [css/main.scss](https://github.com/Dietr/hashi-boilerplate/blob/master/css/main.scss)
- [_scss/*.scss](https://github.com/Dietr/hashi-boilerplate/tree/master/_scss)

## Credits
- [InuitCSS](https://github.com/inuitcss/inuitcss) by [@csswizardry](https://twitter.com/csswizardry) for the ITcss architecture and tons of ideas and best practices.
- [Chopstick](https://github.com/getchopstick/chopstick-boilerplate) by [these contributors](https://github.com/getchopstick/chopstick-boilerplate/graphs/contributors) for a lot of useful patterns, mixins and ideas.
- [AOS](https://github.com/michalsnik/aos) by [Michał Sajnóg](https://github.com/michalsnik) for the animation plugin which makes prototyping animations a lot easier and faster.