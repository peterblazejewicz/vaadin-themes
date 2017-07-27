![Bower version](https://img.shields.io/bower/v/vaadin-themes.svg)
[![Build Status](https://travis-ci.org/vaadin/vaadin-themes.svg?branch=master)](https://travis-ci.org/vaadin/vaadin-themes)
[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/vaadin/vaadin-core-elements?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

# vaadin-themes

`vaadin-themes` is a set of customizable themes for the [Vaadin Core Elements](https://vaadin.com/elements).

<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="vaadin-themes.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->

<!-- [<img src="https://raw.githubusercontent.com/vaadin/vaadin-themes/master/screenshot.png" width="200" alt="Screenshot of vaadin-themes">](https://vaadin.com/elements/-/element/vaadin-themes) -->


## Contributing

1. Fork the `vaadin-themes` repository and clone it locally.

1. Make sure you have [npm](https://www.npmjs.com/) installed.

1. When in the `vaadin-themes` directory, run `npm install` to install dependencies.


## Running demos and tests in browser

1. Install [polyserve](https://www.npmjs.com/package/polyserve): `npm install -g polyserve`

1. When in the `vaadin-themes` directory, run `polyserve --open`, browser will automatically open the component API documentation.

1. You can also open demo or in-browser tests by adding **demo** to the URL, for example:

  - http://127.0.0.1:8080/components/vaadin-themes/demo/index.html

## Following the coding style

We are using [ESLint](http://eslint.org/) for linting JavaScript code. You can check if your code is following our standards by running `gulp lint`, which will automatically lint all `.js` files as well as JavaScript snippets inside `.html` files.


## Creating a pull request

  - Make sure your code is compliant with our code linters: `gulp lint`
  - Check that tests are passing: `npm test`
  - [Submit a pull request](https://www.digitalocean.com/community/tutorials/how-to-create-a-pull-request-on-github) with detailed title and description
  - Wait for response from one of Vaadin Elements team members


## License

Apache License 2.0
