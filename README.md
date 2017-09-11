![Inlight Logo](./doc/inlight-logo.svg)
# Styles

## Contents
- [Requirements](#requirements)
- [Getting started](#getting-started)
- [What's included](#whats-included) 
- [Customisation](#customisation) 

## Requirements
This project uses [NPM 5](https://www.npmjs.com/) for node dependencies. NPM 5 depends on [Node JS](https://nodejs.org)
v4 and above.

## Getting started
```bash
$ npm install git+ssh://git@github.com/inlight-media/inlight-styles.git
```

Then include [all.scss](./scss/all.scss) in your stylesheets.
```SCSS
@import '~inlight-styles/scss/all';
```

## What's included
- [Bootstrap Reboot](https://getbootstrap.com/docs/4.0/content/reboot/) which builds on
[Normalize](https://necolas.github.io/normalize.css). This ensures cross browser consistency and provides an elegant
baseline to build upon.
- The [Bootstrap 4](http://getbootstrap.com/) grid system. Documentation
can be found [here](https://getbootstrap.com/docs/4.0/layout/grid/).

## Customisation
Bootstrap 4 provides plenty of opportunities to override its defaults. Example customisations
can be found in the [examples](./examples) directory.

When including Inlight Styles in your project, remember to insert/include any of your customisations before including
[scss/all.scss](./scss/all.scss). For example:

```SCSS
$grid-columns: 12;
@import '~inlight-styles/scss/all';
```
