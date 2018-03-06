# Chart Format

The chart format object contains fill and line formatting options used extensively throughout the chart. In some contexts only the fill or the line seconds are actually used; this will be noted in the docs where appropriate.

`fill` : [FillFormat](#fill-format)
> Encapsulates a set of fill formatting options.

`line` : [LineFormat](#line-format)
> Encapsulates a set of line formatting options.

### Fill Format

`fillType` : [String](#fill-type)
> The type of fill.

`gradientType` : [String](#gradient-type)
> The type of gradient.

`patternType` : [String](#pattern-type)
> The type of pattern.

`color` : [String]
> HTML hex color code (solid fill only).

`color1` : [String]
> HTML hex color code (gradient or pattern fill only).

`color2` : [String]
> HTML hex color code (gradient or pattern fill only).

`picture` : [PictureFill](#picture-fill)
> Object. Encapsulates the image fill options.

### Line Format

`lineType` : [String](#line-type)
> The drawing style for the line.

`color` : String
> HTML color format.

`weight`: Number
> Width in pixels of the stoke.

### Fill Type

`NONE` : No fill
`SOLID` : Solid fill
`GRADIENT`: Gradient fill
`PATTERN` : Pattern fill
`PICTURE` : Picture fill

### Pattern Type

`DOT_5` : 5%
`DOT_10` : 10%
`DOT_20` : 20%
`DOT_25` : 25%
`DOT_30` : 30%
`DOT_40` : 40%
`DOT_50` : 50%
`DOT_60` : 60%
`DOT_70` : 70%
`DOT_75` : 75%
`DOT_80` : 80%
`DOT_90` : 90%

`LIGHT_DOWN_DIAGONAL` : Light downward diagonal
`DARK_DOWN_DIAGONAL` : Dark downward diagonal
`WIDE_DOWN_DIAGONAL` : Wide downward diagonal

`LIGHT_UP_DIAGONAL` : Light upward diagonal
`DARK_UP_DIAGONAL` : Dark upward diagonal
`WIDE_UP_DIAGONAL` : Wide upward diagonal

`NARROW_VERTICAL` : Narrow vertical
`LIGHT_VERTICAL` : Light vertical
`DARK_VERTICAL` : Dark vertical

`NARROW_HORIZONTAL` : Narrow horizontal
`LIGHT_HORIZONTAL` : Light horizontal
`DARK_HORIZONTAL` : Dark horizontal

### Gradient Type

`VERTICAL`
`VERTICAL_CENTER`
`HORIZONTAL`
`HORIZONTAL_CENTER`

### Picture Fill

`image` : String
> Image file name, should be prepended with: 
> https://d1ttp5jcucct8y.cloudfront.net/reports-images/

`fill` : [PictureFillType](#picture-fill-type)
> The image fill option.

### Line Type

`NONE` : No line should be drawn
`SOLID` : Solid stroke
`DASH` : A dashed stroke
`DASHDOT` : A dash-dot-dash stoke
`DOT` : A dot stroke

### Picture Fill Type

`TILE` : Tile the image in the available space
`STRETCH` Stretch the image to fill the available space