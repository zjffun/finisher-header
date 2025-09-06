> I am not the author, just publish it on npm for your convenience.

# [Finisher Header](https://www.finisher.co/lab/header/)

Online demo: https://www.finisher.co/lab/header/

Configure your own animated header below and use it on your website

by [Finisher](https://www.finisher.co/?ref=header) ― a workflow management company

## Installation

### npm

```shell
npm install finisher-header
```

### pnpm

```shell
pnpm add finisher-header
```

### yarn

```shell
yarn add finisher-header
```


## Usage

```js
import 'finisher-header';

// Get your unique configuration from: https://www.finisher.co/lab/header/
new FinisherHeader({
  "count": 6,
  "size": {
    "min": 1100,
    "max": 1300,
    "pulse": 0
  },
  "speed": {
    "x": {
      "min": 0.1,
      "max": 0.3
    },
    "y": {
      "min": 0.1,
      "max": 0.3
    }
  },
  "colors": {
    "background": "#9138e5",
    "particles": [
      "#6bd6ff",
      "#ffcb57",
      "#ff333d"
    ]
  },
  "blending": "overlay",
  "opacity": {
    "center": 1,
    "edge": 0.1
  },
  "skew": -2,
  "shapes": [
    "c"
  ]
});
```
