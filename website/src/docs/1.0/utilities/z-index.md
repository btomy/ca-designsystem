---
layout: docs
title: Colours
---
# Z-index

| Name                      | Type   | Version                                                                   |
|---------------------------|--------|---------------------------------------------------------------------------|
| `@citizensadvice/z-index` | Utilty | ![npm (scoped)](https://img.shields.io/npm/v/@citizensadvice/z-index.svg) |

## Dependencies

| Name                      | Description                 |
|---------------------------|-----------------------------|
| `@citizensadvice/support` | System wide settings/config |

## Installation

Using your package manager of choice...

```shell
$ npm install @citizensadvice/z-index
```

Then bring into your stylesheets with...

```scss
@import "@citizensadvice/z-index/index.scss";
```

### OR

You can make use of the [unpkg](https://unpkg.com) service, try adding the link below to the head of your `HTML` file.

```html
<link src="https://unpkg.com/@citizensadvice/z-index@latest/build/z-index.css" />
```

## Introduction

Defines the order of elements along the z-axis.

### CSS

```css
.z-index-0       { z-index: $z-index-0       }
.z-index-100     { z-index: $z-index-100     }
.z-index-200     { z-index: $z-index-200     }
.z-index-300     { z-index: $z-index-300     }
.z-index-400     { z-index: $z-index-400     }
.z-index-500     { z-index: $z-index-500     }
.z-index-inherit { z-index: $z-index-inherit }
.z-index-initial { z-index: $z-index-initial }
.z-index-unset   { z-index: $z-index-unset   }
```