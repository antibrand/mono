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

```css
pre {
    font-weight: 400;
}

    @supports( font-variation-settings: normal ) {
        pre {
            font-weight: 535;
            font-variation-settings: 'wdth' 90, 'wght' 535;
        }
    }
}
```

## Static

The static versions are as follows.

### Static Weights

Eight weights available for each of the static widths.

`100, 200, 300, 400, 500, 600, 700, 800`
`thin, ultra-light, light, regular, medium, semi-bold, bold, extra-bold`

### Static Widths

Four widths available for each of the static weights.

`narrow, default, wide, extended`
