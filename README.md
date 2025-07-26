This plugin is an alternative to the GDAL "Rasterize (overwrite with attribute)" tool, available from the ToolBox, with the advantage of creating a new temporary raster for the result, unlike the original tool that modifies the input raster without previously creating a copy of it.

Inputs: An existing raster and a vector layer of polygons with a numeric field, whose values will be transposed into raster pixels in the areas where the raster overlaps with the vector layer. Output: A new, temporary raster.

Please download and read the Manual, available on the homepage.
