# Torsten Mosumgaard Gallery

This is the source code for the website on https://torstenmosumgaard.dk.

![screenshot](./screenshot.png)

- Decent performance
- Modal gallery with URLs
- Keyboard shortcuts (you can tab around or use arrow keys)
- Images are fetched from a Cloudinary account using https://github.com/oskarrough/cloudinary-endpoint

## Prerequisites for developing

* [Git](https://git-scm.com/)
* [Node.js](https://nodejs.org/) (with npm or yarn)
* [Ember CLI](https://ember-cli.com/)
* [Google Chrome](https://google.com/chrome/) (for running the tests)

## Installation

* `git clone git@github.com:oskarrough/torstenmosumgaard-gallery.git`
* `cd torstenmosumgaard-gallery`
* `yarn`

## Development

* `yarn start`
* Visit your app at [http://localhost:4200](http://localhost:4200).

### Running Tests

* `yarn test` (runs once)
* `ember test --server` (visit your tests at [http://localhost:4200/tests](http://localhost:4200/tests))

You can format all scripts using `yarn prettier`. It's a good idea to run this before committing.

### Building

* `yarn build` (production)

### Deploying

The master branch is automatically deployed via netlify.com to https://torstenmosumgaard.dk.
he master branch is automatically deployed via netlify.com to https://torstenmosumgaard.dk.
