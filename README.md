# darkbs

Dark color scheme & some functional [Bootstrap][bs] [components][react]

[![NPM version][npm-image]][npm-url]
[![build status][travis-image]][travis-url]

[bs]: https://github.com/twbs/bootstrap
[react]: https://github.com/facebook/react
[travis-image]: https://travis-ci.org/dk00/darkbs.svg?branch=master
[travis-url]: https://travis-ci.org/dk00/darkbs
[npm-image]: https://img.shields.io/npm/v/darkbs.svg
[npm-url]: https://www.npmjs.com/package/darkbs

## Color Scheme

Black background color scheme, overrides colors only.
Use this by loading the compiled css after Bootstrap.

```html
<link rel="stylesheet" href="//npmcdn.com/darkbs/darkbs.css">
```


## Top-Level API

### `className(options)`
`Object` → `String`

- `options` &lt;Object&gt; | &lt;String&gt;
  - [ ] spacing
  - [x] `text` &lt;Array&gt;
    Add `text-` classes
  - [ ] `text` &lt;Object&gt;
    - [ ] `align`
    - [ ] `transform`
    - [ ] `color`
  - [ ] `color`
  - [ ] `font`
  - [ ] `bg`, `background`
  - [ ] `w`, `width`
  - [ ] `d`, `display`
  - [ ] `pull`
  - [ ] `clearfix`
  - [ ] `pos`, `position`
  - [ ] `invisible`
  - [ ] `sr`, `readerOnly`
  - [ ] `embed`, `embedResponsive`
  - [x] `active` &lt;Boolean&gt;
  - [x] `hidden` &lt;String&gt;
    - `down`, `up`
    Add `.hidden-*-down` and `.hidden-*-up`.

A structural way to use utilitiy classes, return Bootstrap class names.


## Layout

### `container({[fluid=false]})`

- `fluid`: Use `true` for a full width container

### `row()`

### `col([{xs, sm, md, lg, xl}: size])`
- `xs`, `sm`, `md`, `lg`, `xl` &lt;Number&gt; | &lt;Object&gt;
  - `size`
  Column width
  - `offset`, `push`, `pull`
  Column position


## Components

### `button([{color, size, outline, block}])`
- [x] `color`
- [ ] `size`
- [ ] `outline`
- [ ] `block`
