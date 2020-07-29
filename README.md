# mono

A variable monospace font

![cover image](https://raw.githubusercontent.com/antibrand/mono/master/cover.jpg)

## Variable

The variable version has adjustable weight and width.

### Variable Weight

Weight available from `100` to `800`.

### Variable Width

Width available from `50` to `200`.

## Variable Example

Check for font-variation-settings support.

```scss
pre {

    // Default monospace font stack.
    font-family: SFMono-Regular, 'Menlo', 'Consolas', 'Roboto Mono', 'Ubuntu Monospace', 'Noto Mono', 'Oxygen Mono', 'Liberation Mono', 'Courier New', Courier, monospace, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';

    // Set normal weight.
    font-weight: 400;

    // Load the variable font stack if the browser supports it.
    @supports( font-variation-settings: normal ) {
        pre {
            font-family: 'mono', SFMono-Regular, 'Menlo', 'Consolas', 'Roboto Mono', 'Ubuntu Monospace', 'Noto Mono', 'Oxygen Mono', 'Liberation Mono', 'Courier New', Courier, monospace, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
        }
    }

    // Set a slightly narrowed width.
    @supports( font-variation-settings: wdth ) {
        pre {
            font-variation-settings: 'wdth' 90;
        }
    }

    // Set a weight between normal and bold.
    @supports( font-variation-settings: wght ) {
        pre {
            font-variation-settings: 'wght' 535;
        }
    }
}
```

## Static

The static versions are as follows.

### Static Weights

Eight weights available for each of the static widths.

Thin, Ultra-Light, Light, Regular, Medium, Semi-bold, Bold, Extra-bold

`100, 200, 300, 400, 500, 600, 700, 800`

### Static Widths

Four widths available for each of the static weights.

`narrow, default, wide, extended`
