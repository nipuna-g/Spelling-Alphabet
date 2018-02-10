# Nato Spelling Alphabet

*[Live Demo](https://nipuna777.github.io/Spelling-Alphabet/)*

A simple Progressive Web Application that allows you to translate the characters in a string in to the [NATO phonetic alphabet](https://en.wikipedia.org/wiki/NATO_phonetic_alphabet)

# Development Instructions

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Serve Application Locally

```
$ polymer serve
```

Navigate to `http://localhost:8000/` in order to view the page.

## Building Your Application

```
$ polymer build
```

This will create builds of the application in the `build/gh-pages` directory, optimized to be served in production. You can then serve the built versions by giving `polymer serve` a folder to serve from:

```
$ polymer serve build/gh-pages
```

# Deploying to gh-pages

Deployed to gh-pages by pushing the build folder in to the `gh-pages` branch

`$ git subtree push --prefix build/gh-pages/ origin gh-pages`

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
