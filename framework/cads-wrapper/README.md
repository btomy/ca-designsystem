# Wrapper

![npm](https://img.shields.io/npm/v/:package.svg)
![AppVeyor branch](https://img.shields.io/appveyor/ci/:user/:repo/:branch.svg)

## Component type

- Object

## Dependencies:

| Name           | Description                                |
| -------------- | ------------------------------------------ |
| `cads-support` | System-wide global variables and functions |

## Installation

```
$ npm install cads-wrapper
```

```scss
@import "cads-wrapper/index.scss";
```

## Implementation

The `c-wrap` class constrains some contained elements within a `1048px` boundary and centers it in the viewport. It also provides some padding either side, starting out at `16px` on mobile devices and increasing to `32px` on viewports over `555px`.

A few examples of using the `c-wrap` component would be:

- [Grid]()
- [Header]()
- [Footer]()

<!-- prettier-ignore-start -->
```html
<header class="c-global-header">
  <div class="c-wrap">
    ...
  </div>
</header>
```
<!-- prettier-ignore-end -->

There is also a modifier class of `c-wrap--full-width` that’s to be used when you’d like to remove the `max-width` restrictions and should be constructed as such.

<!-- prettier-ignore-start -->
```html
<header class="c-global-header">
  <div class="c-wrap c-wrap--full-width">
    ...
  </div>
</header>
```
<!-- prettier-ignore-end -->