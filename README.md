# Website Optimization Challenge
Optimize a website to gain at least a 90/100 for desktop and mobile on Google's PageSpeed Tool and run at 60 FPS while scrolling. Techniques utilized to optimize website include:
* Javascript and CSS minification
* Image compression
* Improving page's critical rendering path (CRP)
* Responsive images
* Google Chrome development tools

## Table of Contents
* [Installation and Run](#installation-and-run)
* [Optimization Steps](#optimization-steps)
* [Creator](#creator)
* [Copyright and License](#copyright-and-license)

## Installation and Run
Grab code source:
* Clone repository: `git clone https://github.com/brianquach/udacity-nano-front-optimization.git` or download the zip [here](https://github.com/brianquach/udacity-nano-front-optimization/archive/master.zip).
* Navigate to the directory where you cloned the repo or unzipped the file to and open folder `dist`.
* Use your favorite browser to open `index.html`

*Developers (optional)*:
* Install [Gulp](https://github.com/gulpjs/gulp/blob/master/docs/getting-started.md)

## Optimization Steps
* Asynchronously download non-critical javascript by adding `async` script attribute.
* Move importing CSS and Google Fonts to bottom of HTML body.
* Gulp task to compresses all images.
* Gulp task to create thumbnail version of pizzeria.jpg for `index.html`.

## Creator
**Brian Quach**
* <https://github.com/brianquach>
* <http://bkquach.com>

## Copyright and License
Code copyright 2016 Brian Quach. Code released under the [MIT license](https://github.com/brianquach/udacity-nano-front-optimization/blob/master/LICENSE).
