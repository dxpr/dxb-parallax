# DXP Parallax

A lightweight JavaScript plugin for parallax scrolling effects. This is a vanilla JavaScript port of Ian Lunn’s jQuery Parallax v1.1.3.

## Features

- Smooth parallax scrolling
- No dependencies (vanilla JS)
- Works on multiple elements
- Adjustable speed and position

## Installation

You can download the file manually or install via a package manager (if published).

```bash
# Example if using npm in the future
npm install dxb-parallax
```

## Usage

### 1. Import the plugin

```js
import { Parallax, parallax } from './parallax.js';
```

### 2. Apply parallax to a single element

```js
new Parallax(document.querySelector('.hero'), {
  speedFactor: 0.2,
});
```

### 3. Apply to multiple elements

```js
parallax('.parallax', {
  xpos: '50%',
  outerHeight: true,
});
```

## Options

| Option        | Type    | Default | Description                                      |
| ------------- | ------- | ------- | ------------------------------------------------ |
| `xpos`        | string  | `"50%"` | Horizontal background position                   |
| `speedFactor` | number  | `0.1`   | How fast the background moves relative to scroll |
| `outerHeight` | boolean | `true`  | Whether to use outer height (includes margins)   |

## License

MIT — same as the original jQuery version.
