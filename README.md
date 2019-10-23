![React Static Logo](https://raw.githubusercontent.com/react-static/react-static/master/media/react-static-logo-2x.png)

[![Travis CI Build Status](https://travis-ci.org/react-static/react-static.svg?branch=master)](https://travis-ci.org/react-static/react-static) [![David Dependancy Status](https://david-dm.org/react-static/react-static.svg)](https://david-dm.org/react-static/react-static) [![npm package v](https://img.shields.io/npm/v/react-static.svg)](https://www.npmjs.org/package/react-static) [![npm package dm](https://img.shields.io/npm/dm/react-static.svg)](https://npmjs.com/package/react-static) [![Join the community on Spectrum](https://withspectrum.github.io/badge/badge.svg)](https://spectrum.chat/react-static)
[![Github Stars](https://img.shields.io/github/stars/react-static/react-static.svg?style=social&label=Star)](https://github.com/react-static/react-static) [![Twitter Follow](https://img.shields.io/twitter/follow/reactstaticjs.svg?style=social&label=Follow)](https://twitter.com/reactstaticjs)

<br>
<br>

> You are viewing the docs for v7 of React Static. You can browse all historical versions via Github branches!

# React Static

A **progressive static-site generator** for React.

React-Static is a fast, lightweight, and powerful progressive static site generator based on React and its ecosystem. It resembles the simplicity and developer experience you're used to in tools like **Create React App** and has been carefully designed for **performance, flexibility, and user/developer experience**.

## Highlights

- **⚛**️: 100% React (and friends!)
- **🚀**: Blazing fast builds and performance.
- **🚚**: Data Agnostic. Supply your site with data from anywhere, however you want!
- **✂**️: Automatic code and data splitting!
- **💥**: Instant navigation and page views
- **☔**️: Progressively Enhanced and mobile-ready
- **🎯**: SEO Friendly.
- **🥇**: React-centric developer experience.
- **😌**: Painless project setup & migration.
- **💯**: Supports 100% of the React ecosystem. Including CSS-in-JS libraries, custom Query layers like GraphQL, and even Redux.
- **🔥**: Hot Reloadable out-of-the-box. Edit React components, styles and even data in real-time.

## Examples

- [HeadlessCMS.org](https://headlesscms.org) - HeadlessCMS.org
- [StaticGen.com](https://staticgen.com) - StaticGen.com
- [Starbucks: Careers Hub](https://www.starbucks.com/careers/) - Starbucks: Careers Hub
- [Intuit Turbo](http://turbo.com) - Intuit Turbo
- [Timber.io](https://timber.io) - Timber.io

## Installation

1. Install the CLI tool:

    ```
    $ npm i -g react-static
    ```

2. Start a new project!

    ```
    $ react-static create
    ```

3. Need some help?

    ```
    $ react-static --help
    ```

## Documentation

- [Overview](/docs/)
- [Core Concepts](/docs/concepts.md)
- [Guides](/docs/guides/)
- [Configuration](/docs/config.md)
- [API](/docs/api.md)
- [Plugins](/docs/plugins/)

## Migration from a previous version?

The [CHANGELOG](/CHANGELOG.md) contains information on breaking change for each major version. The latest breaking changes along with their migration tips are [located here](/CHANGELOG.md#700)

## What is a progressive static site?

A progressive static site is a website where **every statically exported HTML page is an entry point to a fully-featured automatically-code-split React application**. Just like a normal static site, static progressive websites are capable of loading initial landing pages very quickly, but then extend the user experience by transforming invisibly into a single-page React application.

Once a progressive static site page has loaded its React application it can then do amazing things!

- Prefetch page assets
- Instantly navigate between pages
- Provide interactivity not possible in normal static sites
- Subscribe to and display real-time and dynamic data
- Anything you can imagine within a React application!

# How does it work?

![Flow Chart](https://github.com/react-static/react-static/raw/master/media/flow.png)

React Static gathers your **data**, and **templates** together and intelligently splits them into bite-size static files using webpack and javascript. Once these files have been generated, React Static uses them to render and export a list of **routes** that you provide it into HTML files! After your site has been exported, the resulting **data**, **template**, and **html** files can be transfered to a static file server and browsed as an awesomely fast and performant static website!

But remember, a progressive static site is more than that...

Little did you know that when React Static exported your site, it also generated **a tiny, optimized, and code-split version of your original React application for every page of your site**! After these pages have loaded, React **invisibly** mounts this application to the existing HTML on the page and... 🎉🎉🎉 You are now using the single page React application you originally built! **This application is special, though!** While you browse your website, **pages that you might go to next are automatically preloaded, making navigation to them instantaneous!**.

That's just the beginning! With React Static, you can unleash your creativity and build anything you can imagine with speed and productivity. It even has **awesome plugins** that will help you on your journey!

## Coming from Create React App?

React Static is also a great replacement for the ever popular Create React App CLI. It provides a similar developer experience, zero-config environment, and features, but **without boxing you in.** If you ever need to customize your build system in React Static, there is no need to eject! You can use existing plugins or write your own to customize anything you'd like about the build system. Not building a static site? No worries there, React Static works as an SPA too, even if there is only a single `index.html` file.

## Articles, Videos & Tutorials

- Articles
  - [Introduction and Motivations behind React Static](https://medium.com/@tannerlinsley/%EF%B8%8F-introducing-react-static-a-progressive-static-site-framework-for-react-3470d2a51ebc)
  - [React Static v6!](https://medium.com/@tannerlinsley/react-static-v6-8dbe9fd202d4)
- Videos & Tutorials
  - [Quick Start with Styled Components](https://www.youtube.com/watch?v=KvlTVZPlmgs) (20 min)
  - [Introducing React-Static! How it works and why we built it!](https://www.youtube.com/watch?v=OqbJ5swVpDQ) (80 min)
  - [Using React-Static to replace create-react-app](https://youtu.be/1pBzh7IM1s8) (5 min)

## Support, Community & Chat

Need some help? Have a quick question? [Click here to sign up for the React-Tools spectrum community](https://spectrum.chat/react-static)! We are constantly answering questions, discussing features and helping each other out!

## Contributing, Issues & Bugs

We are always looking for people to help us grow `react-static`'s capabilities and examples. If you have [found a bug, or have a feature request](https://github.com/react-static/react-static/issues/new) let us know!

## License

React Static uses the MIT license. For more information on this license, [click here](/LICENSE).
