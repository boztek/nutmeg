# nutmeg

Nutmeg is a learning tool for PHP educators (and students). It provides a
minimal wrapper around students PHP exercises in a way which handles mistakes
gracefully, helps students and teachers understand their code, and takes care of
basic things which students shouldn't have to write in a PHP class, like table
styles.

## Features

* Prepare a set of PHP exercises for Students to try out
* Web front-end for listing exercises
* Side-by-side comparison of students code and output, in the browser
* PHP syntax highlighting
* Graceful error handling for student's code
* Reskin with CSS (currently limited)
* GPL v2 licenced

## Nutmeg for educators

Nutmeg helps you help student to learn PHP, by providing a way to serve up PHP
exercises in a relatively straightforward way.

### Getting set up

Requirements:
* [Composer](http://getcomposer.org)

1. Download or checkout the latest version of Nutmeg.
2. Run `composer install` to get the dependencies and autoloaders built.
3. Visit `/exercises` to customise the exercises available to your students.
  * The list of exercises is stored in `/exercises/config.yaml`
  * Each exercise is a simple PHP file.

## Nutmeg for students

If you don't already know PHP, Nutmeg is not currently ready for you to start
using it without the supervision of a tutor.

## Roadmap

Nutmeg is in early Alpha. Its basic code loading and viewing features are complete,
but are not extensively tested.

Some of the features we have in mind:

* Load sample code into exercise view
* Better syntax highlighting
* File dependency handling for exercises
* Argument and global variable handlers.
* PHP function reference
* Custom themes
* Code inspection tools (eg Kint, Krumo etc)

## Who made this?

Nutmeg is written and maintained by Chris Skene. Pull requests welcome.

Nutmeg is licenced under GPL v2. Feel free to reuse it as you see fit, but please
consider referencing us if you do.
