# Starter Foundation for Sites Template

[![devDependency Status](https://david-dm.org/zurb/foundation-zurb-template/dev-status.svg)](https://david-dm.org/zurb/foundation-zurb-template#info=devDependencies)

- Run `foundation update` to check
- Run `npm update -g foundation-cli` to update

## Zurb Template

FI's ZURB Template for use with [Foundation for Sites](http://foundation.zurb.com/sites). It has a Gulp-powered build system with these features:

- Handlebars HTML templates with Panini
- Sass compilation and prefixing
- JavaScript module bundling with webpack
- Built-in BrowserSync server
- For production builds:, 
  - CSS compression
  - JavaScript compression
  - Image compression

## What I Done

- Pull out style guide 
  - src/styleguide
  - dist/styleguide.html
  - gulpfile.babel.js (4)
- Uncomment the line that lets you choose what modules to include src/assets/js/app.js
- I'm eliminating what I don't use starting with Abide (also elimintating the references below)
_ Comment out JS src/assets/js/app.js
- Commment out SCSS src/assets/scss/app.scss

## Remember!

- Pull out the JS modules you're not gonna use!
- Run UnCSS in production
- Uncomment any JS you want!
- Uncomment any scss you want!