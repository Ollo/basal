# Basal
"A simple, 2.2kb gzipped css starting point."

[![npm version](https://badge.fury.io/js/basal.svg)](https://badge.fury.io/js/basal)

---
> ## ba·sal
> ˈbāsəl,ˈbāzəl
>
> adjective : `technical`
>
> forming or belonging to a bottom layer or base.

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

**Install the dependencies**
```
npm install
```

Then to develop locally:

```
npm run dev
```
This runs node-sass in watch mode for live reloading if the package is [linked](https://docs.npmjs.com/cli/link).

To build a minified version for production.

```
npm run build
```

### License

[MIT](LICENSE)

### Thanks to the following:

* [Normalize](http://necolas.github.io/normalize.css) for the foundation.
* [Furtive](https://github.com/johnotander/furtive) for the inspiration and head start.

Crafted with <3 by [Joshua Ray](http://ollomedia.com) ([@ollomedia](https://twitter.com/ollomedia)).
