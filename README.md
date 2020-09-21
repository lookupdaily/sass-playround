# Sass playground

A small project to learn about the advantages of sass, how to set up the envirnment needed to use .scss files in a project, and some of the most commonly used syntax.

## Technologies used

- Sass (scss)
- HTML
- NPM

## Getting started

To view the project in the browser you will need [node.js](https://nodejs.org/en/) and [npm](https://www.npmjs.com/) installed.

- Clone this repository and run the follwing in the command line within the project directory:

```shell
npm install
npm run sass:compile
```

- Open [index.html](index.html) in your browser

## Learning notes

## What sass offers:

- variables
- visual nesting
- partials and imports for reuseable CSS - Sass builds on top of CSS import and combines multiple files in compile to prevent multiple HTTP requests which take place when importing multiple CSS files
- functions and mixins - to DRY css
- conditionals
- inheritance - to keep CSS DRY
- operators and culations
- colour functions

## Difference between .sass and .scss

- sass works on indent instead of curly brackets
- scss same syntax as css with additional functionality


## Set up environment

1. Install node sass
2. Add sass script with watch flag ("node-sass -w scss/ -o dist/css/ --recursive) // -o = output