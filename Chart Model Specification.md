# Chart Model JSON Specification

## Top level members

`valueAxis` : [Axis](#axis#) 
> Object. Encapsulates the value axis for the chart.

`secondValueAxis`: [Axis](#axis#) 
> Optional object. Encapsulates the second value axis for the chart. If the chart does not contain a secondary axis this object will not be present.

`categoryAxis`: [Axis](#axis#)
> Object. Encapsulates the category axis for the chart.

`secondCategoryAxis`: [Axis](#axis#) 
> Optional object. Encapsulates the second category axis for the chart. If the chart does not contain a secondary axis this object will not be present.

`chartType`: [String](#chart-type#) 
> The primary chart type.
 
`dataSheet`: [Datasheet](#datasheet#)
> Object. Encapsulates the chart data.

`legend` : [Legend](#legend#)
> Optional object. Encapsulates the chart legend. If the chart legend is not visible this object will not be present.

`series` : [Series\[\]](#series#)
> Array. Contains the series for the chart.

`pieStartAngle` : Number
> The angle in degrees for the first segment of a pie chart.

`plotAreaFormat` : [ChartFormat](#chart-format#)


# Legend

`fill`


# Axis

# Chart Format

`fill` : [FillFormat](#fill-format#)
> Object. Encapsulates a set of fill formatting options.

`line` : [LineFormat](#line-format#)
> Object. Encapsulates a set of line formatting options.

# Fill Format
`fillType` : [String](#fill-type#)
> The type of fill.

`gradientType` : [String](#gradient-type#)
> The type of gradient.

`patternType` : [String](#pattern-type#)
> The type of pattern.

`color` : [String]
> HTML hex color code (solid fill only).

`color1` : [String]
> HTML hex color code (gradient or pattern fill only).

`color2` : [String]
> HTML hex color code (gradient or pattern fill only).

`picture` : [PictureFill](#picture-fill#)
> Object. Encapsulates the image fill options.








