# css-overflow 0.0.6

Css module of single purpose classes for overflow

#### Stats

336 | 48 | 48
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-overflow
```

#### With Git

```
git clone https://github.com/tachyons-css/css-overflow
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-overflow";
```

Then process the CSS using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons-cli path/to/css-file.css > dist/t.css
```

#### Using the CSS

The built CSS is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-overflow">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   OVERFLOW
*/
.of-vis { overflow: visible; }
.of-hid { overflow: hidden; }
.of-scr { overflow: scroll; }
.of-aut { overflow: auto; }
.ofx-vis { overflow-x: visible; }
.ofx-hid { overflow-x: hidden; }
.ofx-scr { overflow-x: scroll; }
.ofx-aut { overflow-x: auto; }
.ofy-vis { overflow-y: visible; }
.ofy-hid { overflow-y: hidden; }
.ofy-scr { overflow-y: scroll; }
.ofy-aut { overflow-y: auto; }
@media screen and (min-width: 48em) {
 .of-vis-ns { overflow: visible; }
 .of-hid-ns { overflow: hidden; }
 .of-scr-ns { overflow: scroll; }
 .of-aut-ns { overflow: auto; }
 .ofx-vis-ns { overflow-x: visible; }
 .ofx-hid-ns { overflow-x: hidden; }
 .ofx-scr-ns { overflow-x: scroll; }
 .ofx-aut-ns { overflow-x: auto; }
 .ofy-vis-ns { overflow-y: visible; }
 .ofy-hid-ns { overflow-y: hidden; }
 .ofy-scr-ns { overflow-y: scroll; }
 .ofy-aut-ns { overflow-y: auto; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .of-vis-m { overflow: visible; }
 .of-hid-m { overflow: hidden; }
 .of-scr-m { overflow: scroll; }
 .of-aut-m { overflow: auto; }
 .ofx-vis-m { overflow-x: visible; }
 .ofx-hid-m { overflow-x: hidden; }
 .ofx-scr-m { overflow-x: scroll; }
 .ofx-aut-m { overflow-x: auto; }
 .ofy-vis-m { overflow-y: visible; }
 .ofy-hid-m { overflow-y: hidden; }
 .ofy-scr-m { overflow-y: scroll; }
 .ofy-aut-m { overflow-y: auto; }
}
@media screen and (min-width: 64em) {
 .of-vis-l { overflow: visible; }
 .of-hid-l { overflow: hidden; }
 .of-scr-l { overflow: scroll; }
 .of-aut-l { overflow: auto; }
 .ofx-vis-l { overflow-x: visible; }
 .ofx-hid-l { overflow-x: hidden; }
 .ofx-scr-l { overflow-x: scroll; }
 .ofx-aut-l { overflow-x: auto; }
 .ofy-vis-l { overflow-y: visible; }
 .ofy-hid-l { overflow-y: hidden; }
 .ofy-scr-l { overflow-y: scroll; }
 .ofy-aut-l { overflow-y: auto; }
}
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Authors

* [mrmrs](http://mrmrs.io)
* [johno](http://johnotander.com)

## License

ISC
