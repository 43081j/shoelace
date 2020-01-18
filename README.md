# Shoelace

A forward-thinking component library built with Web Components.

Objective:

1. Design a framework-agnostic component library 🧩
2. Be able to load it from a CDN ⚡️
3. Fully customize it with CSS variables — no need to build it yourself! 🎨

Designed and developed in New Hampshire by [Cory LaViska](https://twitter.com/claviska).

## Installation

TODO

## Usage

TODO

## Developers

TODO

## Bugs, Questions, & Support

TODO

## Shadow DOM

Most Shoelace components use Shadow DOM with the exception of form controls. This is for your convenience, since form controls inside a shadow DOM aren't submitted with standard HTML forms. In the future, when StencilJS and browsers add support for [Form-associated Custom Elements](https://html.spec.whatwg.org/multipage/custom-elements.html#custom-elements-face-example), it would be nice if all components can use Shadow DOM.

## Attribution

- Theme colors and form controls inspired by [Element](element.eleme.io)
- Popover positioning is handled by [Popper.js](https://popper.js.org/)
- Tooltips are provided by [Tippy.js](https://atomiks.github.io/tippyjs/)
