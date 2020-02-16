Shoelace is a framework-agnostic UI library built with [Web Components](web-components.md). Here's why you should try it:

- 🧩 Works with all frameworks
- ⚡️ Loads over CDNs
- 🎨 Fully customizable without a preprocessor

## Quick Start

Add the following code before the `</head>` tag.

```html
<script type="module" src="/dist/shoelace/shoelace.esm.js"></script>
<script nomodule src="/dist/shoelace/shoelace.js"></script>
```

Then add some components to your page.

```html
<sl-input type="search" placeholder="Search"></sl-input>
<sl-button type="primary">Go</sl-button>
```

Congratulations, you're using Shoelace! 🥳

!> Don't want to use the CDN version? [You can install it instead](installing.md)


## About

Shoelace was designed and developed in New Hampshire by [Cory LaViska](https://twitter.com/claviska). It is available to use freely under the terms of the MIT License.

- 🤔 Questions can be posted on [Stack Overflow](https://stackoverflow.com/questions/tagged/shoelace) using the `shoelace` tag
- 🐞 Bugs and feature requests can be submitted on the [issue tracker](https://github.com/claviska/shoelace/issues)
- 👨🏻‍💻 The author can be reached on [Twitter](https://twitter.com/claviska)

Special thanks to the following projects for making Shoelace possible:

- Components are built and compiled by [Stencil](https://stenciljs.com/)
- Theme colors and form controls are inspired by [Element](https://element.eleme.io/)
- Popover positioning is handled by [Popper.js](https://popper.js.org/)
- Tooltips are powered by [Tippy.js](https://atomiks.github.io/tippyjs/)
- Docs are powered by [Docsify](https://docsify.js.org/)

© {{year}} A Beautiful Site, LLC
