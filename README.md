# design-maths
Layout mathematics for Web Design


# Typography
[Google Material Design Spec on Typography](http://www.google.com/design/spec/style/typography.html)

## Type weights
Six weights: Thin, Light, Regular, Medium, Bold, and Black.

The basic set of styles are based on a typographic scale:

```
// semantics
 caption body   subhead title  headline display 1/2/3/4

// scaleable pixels
 12,     14,    16,     20,    24,      34,     45,     56,     112

// ratio: x_{n+1}/x_n
 1,      1.166, 1.143,  1.25,  1.2,     1.417,  1.323,  1.244,  2

// ratio: x_{n+2}/x_n
                1.333,  1.428, 1.5,     1.7,    1.875,  1.647   2.488

 1,    1.166,   1.333,  1.666, 2,       2.833,  3.75,   4.666,  9.333
.857,  1,       1.143,  1.428, 1.714,   2.428,  3.214,  4,      8


// weights
                        500,   400,     400,    400,    400,    300


// leading
 20,      24,    24,    28,    32,      40,     48

// ratio
 1.666,   1.714, 1.5,   1.4,   1.333,   1.176   1.0666
```

Page Navigation/ App Bar: Medium 20sp

Button: Medium 14sp, all caps


## Line height

Line wrapping only applies to Body, Subhead, Headline, and the smaller Display styles. All other styles should exist as single lines.


# Layout
[Google Spec Layout - Structure](htps://www.google.com/design/spec/layout/structure.html)

## Grid

### Mobile 48/56dp, Tablet/Desktop 64dp

Horizontal: Gutter 16
