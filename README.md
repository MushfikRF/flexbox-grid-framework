Flexbox Grid
===========

The framework link: [flexboxgrid.com](http://flexboxgrid.com)  

All kind of CDN  link [cdnjs.com](https://cdnjs.com)   &   [jsdelivr.com](https://www.jsdelivr.com/)

Grid based on the `flex` display property.




Install
---------
### npm
`npm i flexboxgrid --save`

### bower
`bower install flexboxgrid`

### cdn
```
<link rel="stylesheet" href="https://cdn.jsdelivr.net/flexboxgrid/6.3.1/flexboxgrid.min.css" type="text/css" >
```

### css
* [Development](https://raw.githubusercontent.com/kristoferjoseph/flexboxgrid/master/dist/flexboxgrid.css)
* [Production](https://raw.githubusercontent.com/kristoferjoseph/flexboxgrid/master/dist/flexboxgrid.min.css)

Add the `flexboxgrid.css` __development__ or `flexboxgrid.min.css` __production__ to your html page.

```
<link rel="stylesheet" href="css/flexboxgrid.min.css" type="text/css">
```

# flexbox Grid 2
[![npm version](https://badge.fury.io/js/flexboxgrid2.svg)](https://badge.fury.io/js/flexboxgrid2)

Modern 12 column grid system based on flex property.

→ [Documentation](https://evgenyrodionov.github.io/flexboxgrid2/)
## Motivation
Forked from [kristoferjoseph/flexboxgrid](https://github.com/kristoferjoseph/flexboxgrid) because original project seems abandoned ([kristoferjoseph/flexboxgrid#236](https://github.com/kristoferjoseph/flexboxgrid/pull/236), [kristoferjoseph/flexboxgrid#229](https://github.com/kristoferjoseph/flexboxgrid/pull/229), [kristoferjoseph/flexboxgrid#211](https://github.com/kristoferjoseph/flexboxgrid/pull/211), etc).

## Breakpoints
- `xs`: 0..575px
- `sm`: 576..767px
- `md`: 768..991px
- `lg`: 992..1199px
- `xl`: 1200px+
- `.container` padding: 8px
- `.container` width: $breakpoint - 16px
- `.col-*` padding: 8px

## Install
### yarn
`yarn add flexboxgrid2`

### npm
`npm i -S flexboxgrid2`

# Usage
### webpack
```js
import 'flexboxgrid2'
// or if you use airbnb-config-eslint which explicitly wants .css extension
import 'flexboxgrid2/flexboxgrid2.css'
```

### unpkg.com CDN
```html
<link rel="stylesheet" href="https://unpkg.com/flexboxgrid2@[version]/flexboxgrid2.css">
``` 

Replace `[version]` with current version, f.e. `7.2.1`
