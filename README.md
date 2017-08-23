# FI's starter Foundation for Sites template

[![devDependency Status](https://david-dm.org/zurb/foundation-zurb-template/dev-status.svg)](https://david-dm.org/zurb/foundation-zurb-template#info=devDependencies)

## Zurb Template

FI's ZURB Template for use with [Foundation for Sites](http://foundation.zurb.com/sites). It has a Gulp-powered build system with these features:

- Handlebars HTML templates with Panini
- Sass compilation and prefixing
- JavaScript module bundling with webpack
- Built-in BrowserSync server
- For production builds:
  - CSS compression
  - JavaScript compression
  - Image compression

## What I Done

- Pull out style guide 
  - src/styleguide
  - dist/styleguide.html
  - gulpfile.babel.js (4)
- In src/assets/js/app.js uncomment the line that lets you choose what modules to include
- I'm eliminating what I don't use starting with Abide (also elimintating the references below)

## Remember!

- Pull out the JS modules you're not gonna use!
- Run UnCSS in production

## Notes

- I'm using UnCSS inproduction so I guess don't worry about stripping all the CSS I'm not using


