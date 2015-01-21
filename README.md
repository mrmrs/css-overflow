# CSS OVERFLOW

  Mobile-first classes for css-overflow.
  Set the desired css-overflow on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
Grab the css partial from github and include it in your project or alternatively
you can install it via npm:
```
npm install --save-dev css-overflow
```
View on [npm](https://www.npmjs.org/package/css-overflow)


## File Size

1.8K overflow.css
1.4K overflow.min.css
294B minified and gzipped

## The Code
```
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

@media screen and (min-width: 48em) and (max-width: 64em) {
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

@media screen and (min-width: 64em)  {
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

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2015 @mrmrs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

