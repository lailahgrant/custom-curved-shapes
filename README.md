# Curved Custom DIV Shapes using Pure CSS and SVG
There are two ways to do this:-
- Pure CSS
- SVG

a) Pure CSS
- Add an empty `div` .
```

<div class="curve"></div>

```

- Add the `curves` using Pseudo elements : 
- - `::before`
- - `::after`

Advantage of using Pseudo elements `::before` and `::after`
- They allow us to insert content on webpage without it being in the html page.

| Single Div   | Multiple Divs |
| ------------ | ------------- |
| ::before     | div           |
| ::after      | div           |

- Pure CSS is more suitable for curves like `circles`, `single ellipses`.


b) SVGs
- More complex shapes and curves.
- [Custom Shape Dividers](https://www.shapedivider.app/)
- Add svg tags and css.


Link to preview is as follows:
[curves](https://custom-curved-shapes.netlify.app/)