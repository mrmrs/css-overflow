# css-overflow

Functional CSS for overflow

## Filesize

| File | Size |
|------|------|
| `dist/overflow.css` | 2069 bytes |
| `dist/overflow.min.css` | 1407 bytes (272 Gzipped) |

## Install

```sh
npm install css-overflow
```

## Usage

### Import

```css
@import "css-overflow";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-overflow/dist/overflow.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-overflow/dist/overflow.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.of-vis` | `overflow: visible;` |
| `.of-hid` | `overflow: hidden;` |
| `.of-scr` | `overflow: scroll;` |
| `.of-aut` | `overflow: auto;` |
| `.ofx-vis` | `overflow-x: visible;` |
| `.ofx-hid` | `overflow-x: hidden;` |
| `.ofx-scr` | `overflow-x: scroll;` |
| `.ofx-aut` | `overflow-x: auto;` |
| `.ofy-vis` | `overflow-y: visible;` |
| `.ofy-hid` | `overflow-y: hidden;` |
| `.ofy-scr` | `overflow-y: scroll;` |
| `.ofy-aut` | `overflow-y: auto;` |
| `.of-vis-s` | `overflow: visible;` |
| `.of-hid-s` | `overflow: hidden;` |
| `.of-scr-s` | `overflow: scroll;` |
| `.of-aut-s` | `overflow: auto;` |
| `.ofx-vis-s` | `overflow-x: visible;` |
| `.ofx-hid-s` | `overflow-x: hidden;` |
| `.ofx-scr-s` | `overflow-x: scroll;` |
| `.ofx-aut-s` | `overflow-x: auto;` |
| `.ofy-vis-s` | `overflow-y: visible;` |
| `.ofy-hid-s` | `overflow-y: hidden;` |
| `.ofy-scr-s` | `overflow-y: scroll;` |
| `.ofy-aut-s` | `overflow-y: auto;` |
| `.of-vis-m` | `overflow: visible;` |
| `.of-hid-m` | `overflow: hidden;` |
| `.of-scr-m` | `overflow: scroll;` |
| `.of-aut-m` | `overflow: auto;` |
| `.ofx-vis-m` | `overflow-x: visible;` |
| `.ofx-hid-m` | `overflow-x: hidden;` |
| `.ofx-scr-m` | `overflow-x: scroll;` |
| `.ofx-aut-m` | `overflow-x: auto;` |
| `.ofy-vis-m` | `overflow-y: visible;` |
| `.ofy-hid-m` | `overflow-y: hidden;` |
| `.ofy-scr-m` | `overflow-y: scroll;` |
| `.ofy-aut-m` | `overflow-y: auto;` |
| `.of-vis-l` | `overflow: visible;` |
| `.of-hid-l` | `overflow: hidden;` |
| `.of-scr-l` | `overflow: scroll;` |
| `.of-aut-l` | `overflow: auto;` |
| `.ofx-vis-l` | `overflow-x: visible;` |
| `.ofx-hid-l` | `overflow-x: hidden;` |
| `.ofx-scr-l` | `overflow-x: scroll;` |
| `.ofx-aut-l` | `overflow-x: auto;` |
| `.ofy-vis-l` | `overflow-y: visible;` |
| `.ofy-hid-l` | `overflow-y: hidden;` |
| `.ofy-scr-l` | `overflow-y: scroll;` |
| `.ofy-aut-l` | `overflow-y: auto;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.of-vis-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/overflow.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/overflow.css` — formatted
- `dist/overflow.min.css` — minified

## License

MIT
