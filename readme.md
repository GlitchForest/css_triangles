#CSS Triangle SASS Mixix

Import the mixin partial into your .scss or .sass file:
`@import "triangle";`

Include the mixin
`@include triangle($size, $color, $direction)`

The triangle mixing take 3 parameters:

1. _$size_: width of the long edge of the triangle, must specify units
2. _$color_: will take hex-color (must include # sign) or a color name.
3. _$direction_: The direction the triangle will point; up, right, down or left