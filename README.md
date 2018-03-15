# Performance matters

## Project setup

This project serves an adapted version of the [Bootstrap documentation website](http://getbootstrap.com/). It is based on the [github pages branche of Bootstrap](https://github.com/twbs/bootstrap/tree/gh-pages).

Differences from actual Bootstrap documentation:

- Added custom webfont
- Removed third party scripts
- The src directory is served with [Express](https://expressjs.com/).
- Templating is done with [Nunjucks](https://mozilla.github.io/nunjucks/)

## Getting started

- Install dependencies: `npm install`
- Serve: `npm start`
- Expose localhost: `npm run expose`

## Branches
There are 5 branches in this project
* Master
* CSS-A
* JS-A
* IMG-A
* all

In the master you can find the original project. This project will be the slowest of all. When you enter a different branch you can find the result in the readme.md. This file will contain all the conclusions and results of that project.
Each branch has a diffrent approach of speeding up the page. These tests were all performed on a Chrome browser. All pages are tested on the home page (except the image branch).

The all branch will show all the results combined. 

I didn't try all methods on this project. I also didn't try gZip cause I didn't have a server at the time. I assume it also improves the speed of the page.
