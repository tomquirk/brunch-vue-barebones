# Brunch Vue Barebones

A _barebones_ Brunch skeleton for [Vue.js](https://vuejs.org/) - minimal dependencies!

Unlike other skeletons with Vue, `brunch-vue-barebones` is based on the official scaffold provided by the Vue.js core team ([vue-cli](https://github.com/vuejs/vue-cli)). The only dependencies are `vue` and `vue-router`; configure it how you like!

Thanks to [https://github.com/nblackburn](@nblackburn) for his work on [vue-brunch](https://github.com/nblackburn/vue-brunch)

## Installation

1. Install Brunch globally

```bash
npm install -g brunch
```

2. Create a new Brunch project using _this_ skeleton

```bash
brunch new -s vue
```

### Manual Install

You can clone this repo manually!

## Getting Started

> Taken from the official Brunch docs

* Install (if you don't have them):
  * [Node.js](http://nodejs.org): `brew install node` on OS X
  * [Brunch](http://brunch.io): `npm install -g brunch`
  * Brunch plugins and app dependencies: `npm install`
* Run:
  * `npm start` — watches the project with continuous rebuild. This will also launch HTTP server with [pushState](https://developer.mozilla.org/en-US/docs/Web/Guide/API/DOM/Manipulating_the_browser_history).
  * `npm run build` — builds minified project for production
* Learn:
  * `public/` dir is fully auto-generated and served by HTTP server.  Write your code in `app/` dir.
  * Place static files you want to be copied from `app/assets/` to `public/`.
  * [Brunch site](http://brunch.io), [Getting started guide](https://github.com/brunch/brunch-guide#readme)

## TODO

* Add support for Hot Module Reloading with [hmr-brunch](https://github.com/brunch/hmr-brunch)
