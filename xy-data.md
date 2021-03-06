# XY Data

`series` : [XYSeries\[\]](#xy-series)
> Array containing the XY data for each series

`seriesKeys` : [CodeResponseKey\[\]](code-response-key.md)
> Array of mTAB response keys for each series

### XY Series

`name` : String
> The series name

`dataFormat` : [String](data-format-type.md)
> The data type of the data

`plotSecondaryAxis` : Boolean
> If true, the series is plotted on the secondary axis

`values` : [XYDataPoint\[\]](#xy-data-point)
> Array of XY data points for the series

`categoryKeys` : [CodeResponseKey\[\]](code-response-key.md)
> Array of mTAB response keys for each category

### XY Data Point

`x` : Number
> Optional. The X value of the point

`y` : Number
> Optional. The Y value of the point

`z` : Number
> Optional. The Z value of the point

`name` : String
> The name of the point
