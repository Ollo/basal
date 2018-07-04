# Basal

[![npm version](https://badge.fury.io/js/basal.svg)](https://badge.fury.io/js/basal)

A lightweight, css microframework. Minimal by design.

## Installation

```
npm i basal
```

Then from within your project you can either import the partials
```
@import '<npm location>/basal/src/scss/<partial>'
```

Or import and bundle the default styles.

```
import 'basal/dist/basal.css'
```

### Development

This is an intentionally simple package with low complexity.
As such there are no associated tests or linters in place.

To make changes

Fork the repo https://github.com/ollo/basal and clone it locally.


**Install the dependencies**
```
npm install
```

Run node-sass in watch mode for live reloading when package is linked.

```
npm run dev
```

Build minified version for production.

```
npm run build
```

### License

[MIT](LICENSE)

### Thanks to the following:

* [Normalize](http://necolas.github.io/normalize.css) for the foundation.
* [Furtive](https://github.com/johnotander/furtive) for the inspiration and head start.

Crafted with <3 by [Joshua Ray](http://ollomedia.com) ([@ollomedia](https://twitter.com/ollomedia)).
