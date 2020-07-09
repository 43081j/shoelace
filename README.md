# Shoelace

A forward-thinking library of web components.

- Works with all frameworks 🧩
- Works with CDNs 🚛
- Fully customizable with CSS 🎨
- Open source 😸

Designed in New Hampshire by [Cory LaViska](https://twitter.com/claviska).

---

Documentation: [shoelace.style](https://shoelace.style)

Source: [github.com/claviska/shoelace](https://github.com/claviska/shoelace)

Twitter: [@shoelaceUI](https://twitter.com/shoelaceui)

---

## Shoemakers 🥾

Shoemakers, or "developers," can use this documentation to learn how to build Shoelace from source.

**You don't need to do any of this to use Shoelace!** This page is for people who want to contribute to the project, tinker with the source, or create a custom build of Shoelace.

If that's not what you're trying to do, the [documentation website](https://shoelace.style) is where you want to be.

### What are you using to build Shoelace?

Components are built with [Stencil](https://stenciljs.com/), a compiler that generates standards-based web components. The source code is a combination of TypeScript + JSX (TSX). Stylesheets make limited use of SCSS (see the contributor guidelines for details).

The build is done through a combination of Stencil's CLI and a handful of custom scripts.

### Forking the Repo

Start by [forking the repo](https://github.com/claviska/shoelace/fork) on GitHub, then clone the repo locally and install dependencies.

```sh
git clone https://github.com/YOUR_GITHUB_USERNAME/shoelace
cd shoelace
npm install
```

### Developing

Once you've cloned the repo, run the following command.

```sh
npm run start
```

This will spin up the Shoelace dev server. Note that the dev server requires ports 4000, 4001, and 4002 to be available.

After the initial build, a browser will open at `http://localhost:4000`.

Hot module reloading (HMR) is enabled for components, so changes will instantly reflect in the browser as you work.

The documentation is powered by Docsify, which uses raw markdown files to generate pages. As such, no static files are built for the docs. Unfortunately, changes to _documentation pages_ will trigger a page refresh (no HMR).

### Building

To generate a production build, run the following command.

```sh
npm run build
```

### Contributing

Shoelace is an open source project and contributions are encouraged! If you're interesting in contributing, please review the [contribution guidelines](CONTRIBUTING.md).

## License

Shoelace is designed in New Hampshire by [Cory LaViska](https://twitter.com/claviska). It’s available under the terms of the MIT license.

Designing, developing, and supporting this library requires a lot of time, effort, and skill. I’d like to keep it open source so everyone can use it, but that doesn’t provide me with any income.

**Therefore, if you’re using my software to make a profit,** I respectfully ask that you help [fund its development](https://github.com/sponsors/claviska) by becoming a sponsor. There are multiple tiers to choose from with benefits at every level, including prioritized support, bug fixes, feature requests, and advertising.

👇 Your support is very much appreciated! 👇

- [Become a sponsor](https://github.com/sponsors/claviska)
- [Star on GitHub](https://github.com/claviska/shoelace/stargazers)
- [Follow on Twitter](https://twitter.com/shoelaceui)

Have fun creating! 🥾
