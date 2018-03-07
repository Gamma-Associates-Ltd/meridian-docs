# Chart Format

The chart format object contains fill and line formatting options used extensively throughout the chart. In some contexts only the fill or the line sections are actually used; this will be noted in the docs where appropriate.

`fill` : [FillFormat](#fill-format)
> Fill formatting options

`line` : [LineFormat](#line-format)
> Line formatting options

### Fill Format

`fillType` : [String](#fill-type)
> The type of fill

`gradientType` : [String](#gradient-type)
> The type of gradient

`patternType` : [String](#pattern-type)
> The type of pattern

`color` : String
> HTML color code (solid fill only).

`color1` : String
> HTML color code (gradient or pattern fill only).

`color2` : String
> HTML color code (gradient or pattern fill only).

`picture` : [PictureFill](#picture-fill)
> Object. Encapsulates the image fill options.

### Line Format

`lineType` : [String](#line-type)
> The drawing style for the line

`color` : String
> HTML color format

`weight`: Number
> Width in pixels of the stoke

### Fill Type

	NONE
	SOLID
	GRADIENT
	PATTERN
	PICTURE

### Pattern Type

	DOT_5
	DOT_10
	DOT_20
	DOT_25
	DOT_30
	DOT_40
	DOT_50
	DOT_60
	DOT_70
	DOT_75
	DOT_80
	DOT_90
	LIGHT_DOWN_DIAGONAL
	DARK_DOWN_DIAGONAL
	WIDE_DOWN_DIAGONAL
	LIGHT_UP_DIAGONAL
	DARK_UP_DIAGONAL
	WIDE_UP_DIAGONAL
	NARROW_VERTICAL
	LIGHT_VERTICAL
	DARK_VERTICAL
	NARROW_HORIZONTAL
	LIGHT_HORIZONTAL
	DARK_HORIZONTAL

### Gradient Type

	VERTICAL
	VERTICAL_CENTER
	HORIZONTAL
	HORIZONTAL_CENTER

### Picture Fill

`image` : String
> Image file name, should be prepended with: 
> https://d1ttp5jcucct8y.cloudfront.net/reports-images/

`fill` : [PictureFillType](#picture-fill-type)
> The image fill option.

### Line Type

	NONE
	SOLID
	DASH
	DASHDOT
	DOT

### Picture Fill Type

	TILE
	STRETCH