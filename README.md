# Tailwind CSS Border Styles Plugin

![Package Version](https://img.shields.io/npm/v/tailwindcss-border-styles?style=flat-square)
![Package Total Downloads](https://img.shields.io/npm/dt/tailwindcss-border-styles?style=flat-square)

## Requirements

- [Tailwind CSS](https://tailwindcss.com/) >= v1.0.0

## Installation

Install via Yarn:

```sh
$ yarn add tailwindcss-border-styles
```

## Usage

```js
// tailwind.config.js
{
  plugins: [
    require('tailwindcss-border-styles')(),
  ],
}
```

This plugin generates the following utilities:

```css
.border-t-solid {
  border-top-style: solid;
}

.border-t-dashed {
  border-top-style: dashed;
}

.border-t-dotted {
  border-top-style: dotted;
}

.border-t-double {
  border-top-style: double;
}

.border-t-none {
  border-top-style: none;
}

.border-r-solid {
  border-right-style: solid;
}

.border-r-dashed {
  border-right-style: dashed;
}

.border-r-dotted {
  border-right-style: dotted;
}

.border-r-double {
  border-right-style: double;
}

.border-r-none {
  border-right-style: none;
}

.border-b-solid {
  border-bottom-style: solid;
}

.border-b-dashed {
  border-bottom-style: dashed;
}

.border-b-dotted {
  border-bottom-style: dotted;
}

.border-b-double {
  border-bottom-style: double;
}

.border-b-none {
  border-bottom-style: none;
}

.border-l-solid {
  border-left-style: solid;
}

.border-l-dashed {
  border-left-style: dashed;
}

.border-l-dotted {
  border-left-style: dotted;
}

.border-l-double {
  border-left-style: double;
}

.border-l-none {
  border-left-style: none;
}
```

as well as the responsive variants if you have `responsive` set on [`borderStyle`](https://github.com/tailwindcss/tailwindcss/blob/master/stubs/defaultConfig.stub.js#L435).

## Testing

Tests are handled with [Jest](https://github.com/facebook/jest) and can be ran using:

```sh
$ yarn run test
```

## Bug Reports

If you discover a bug in Tailwind CSS Border Styles, please [open an issue](https://github.com/log1x/tailwindcss-border-styles/issues).

## Contributing

Contributing whether it be through PRs, reporting an issue, or suggesting an idea is encouraged and appreciated.

## License

Tailwind CSS Border Styles provided under the [MIT License](https://github.com/log1x/tailwindcss-border-styles/blob/master/LICENSE.md).
