# [Diend](https://diend.vuminhnhat.xyz)

Diend is a **modern CSS framework** based on [Flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Using_CSS_flexible_boxes).

![Github](https://img.shields.io/github/v/release/nhatcoder2k3/diend?logo=Diend)
[![npm](https://img.shields.io/npm/v/diend.svg)][npm-link]
[![npm](https://img.shields.io/npm/dm/diend.svg)][npm-link]
[![](https://data.jsdelivr.com/v1/package/npm/diend/badge)](https://www.jsdelivr.com/package/npm/diend)
[![Awesome][awesome-badge]][awesome-link]
[![Join the chat at https://gitter.im/nhatcoder2k3/diend](https://badges.gitter.im/nhatcoder2k3/diend.svg)](https://gitter.im/nhatcoder2k3/diend)
[![Build Status](https://travis-ci.org/nhatcoder2k3/diend.svg?branch=master)](https://travis-ci.org/nhatcoder2k3/diend)

<a href="https://diend.vuminhnhat.xyz"><img src="https://raw.githubusercontent.com/nhatcoder2k3/diend/master/docs/images/diend-banner.png" alt="Diend: a Flexbox CSS framework" style="max-width:100%;" width="600"></a>

## Quick install

Diend is constantly in development! Try it out now:

### NPM

```sh
npm install diend
```

**or**

### Yarn

```sh
yarn add diend
```

### Bower

```sh
bower install diend
```

### Import

After installation, you can import the CSS file into your project using this snippet:

```sh
@import 'diend/css/diend.css'
```

### CDN

[https://www.jsdelivr.com/package/npm/diend](https://www.jsdelivr.com/package/npm/diend)

Feel free to raise an issue or submit a pull request.

## CSS only

Diend is a **CSS** framework. As such, the sole output is a single CSS file: [diend.css](https://github.com/nhatcoder2k3/diend/blob/master/css/diend.css)

You can either use that file, "out of the box", or download the Sass source files to customize the [variables](https://diend.vuminhnhat.xyz/documentation/overview/variables/).

There is **no** JavaScript included. People generally want to use their own JS implementation (and usually already have one). Diend can be considered "environment agnostic": it's just the style layer on top of the logic.

## Browser Support

Diend uses [autoprefixer](https://github.com/postcss/autoprefixer) to make (most) Flexbox features compatible with earlier browser versions. According to [Can I use](https://caniuse.com/#feat=flexbox), Diend is compatible with **recent** versions of:

- Chrome
- Edge
- Firefox
- Opera
- Safari

Internet Explorer (10+) is only partially supported.

## Documentation

The documentation resides in the [docs](docs) directory, and is built with the Ruby-based [Jekyll](https://jekyllrb.com/) tool.

Browse the [online documentation here.](https://diend.vuminhnhat.xyz/documentation/overview/start/)

## Related projects


## Copyright and license ![Github](https://img.shields.io/github/license/nhatcoder2k3/diend?logo=Github)

Code copyright 2022 Vũ Minh Nhật. Code released under [the MIT license](https://github.com/nhatcoder2k3/diend/blob/master/LICENSE).

[npm-link]: https://www.npmjs.com/package/diend
[awesome-link]: https://github.com/awesome-css-group/awesome-css
[awesome-badge]: https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg
