The GridLayout is a layout that arranges its child elements in a table structure of rows and columns. A cell can contain multiple child elements. Each one can span over multiple rows and columns, and even overlap the others. The GridLayout has one column and one row by default. To add additional columns and rows, you have to specify column definition items (separated by commas) to the columns property and row definition items (separated by commas) to the rows property of the GridLayout. The width of a column and the height of a row can be specified as an absolute amount of pixels, or automatically and by using the start sign (*) for relative percentages.

> **Note**: While percentage values are **not** supported for creating rows and columns, you can use the start sign (**`*`**) to take space based on relative percentage.
For example, let's assume that we have the following setup `rows="*, 2*, 2*"`. The GridLayout will take all the available space (meaning the space given by its parent or the space set via the `height` property), will create three rows and will divide the space to 5 equal parts (as we have a total of `5*`). The first row will take one part (`*`), while the second and the third rows will take two parts (`2*`) meaning they will be twice as big compared to the first row. The setup would be equal to setting `20%, 40%, 40%`.

**API Reference for** [GridLayout Class](http://docs.nativescript.org/api-reference/modules/_ui_layouts_grid_layout_.html)

A basic usage and definition of GridLayout,its rows and columns and its children in HTML.

<snippet id='grid-layout-html'/>
