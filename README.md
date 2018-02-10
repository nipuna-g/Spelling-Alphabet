# Nato Spelling Alphabet

A simple Progressive Web Application that allows you to translate the characters in a string in to the [NATO phonetic alphabet](https://en.wikipedia.org/wiki/NATO_phonetic_alphabet)

# Setting up Dev environment

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Viewing Your Application

```
$ polymer serve
```

## Building Your Application

```
$ polymer build
```

This will create builds of your application in the `build/` directory, optimized to be served in production. You can then serve the built versions by giving `polymer serve` a folder to serve from:

```
$ polymer serve build/default
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.

# Deploying to gh-pages

`$ git subtree push --prefix build/gh-pages/ origin gh-pages`