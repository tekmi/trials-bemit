# Techday BEMIT

This is the repository for the techday BEMIT. This repository will generate a
static site and the toolkit. 

For the initial assignment, please check Brian van Burken repository https://github.com/brianvanburken/techday-bemit, since this 
little project emerged from his blueprint project.

## Getting started

### Requirements

- Node.js 8.x.x or higher

### Installation

1.  Clone project
2.  Run `npm install`

## Development

Run `npm run dev`\
If the site is not automatically opened, visit: [http://localhost:3000](http://localhost:3000).

For the CSS we use [Sass](https://sass-lang.com/) to work more efficient. The
structure is setup using [ITCSS](https://www.xfive.co/blog/itcss-scalable-maintainable-css-architecture/)
and the methodology for writing CSS is [BEM](http://getbem.com/). More detailed
explanation can be found in the comments inside the `src/toolkit/index.sass` file.

All the files required need to be imported in `src/toolkit/index.sass` to be exposed.

HTML for components can be written in `index.html` in the root of this project.

## Production

Run `npm run build`.\
This will create a folder called `dist` that contains the static build of the toolkit
and corresponding images.
