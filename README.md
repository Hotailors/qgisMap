# qgisMap

## SVG world map generator

Countires folder contains prepared world map in .shp file. You can open and edit this map 
using QGIS software [QGIS website](https://www.qgis.org/en/site/index.html).

To generate SVG map Kartograph.py was used - [Kartograph](http://kartograph.org/docs/kartograph.py/#installing-kartograph-py).

Kartograph requires config.json file were you can define options like 'attributes' already included.

Execute following command from countries/ directory to generate .svg

`kartograph config.json -o mymap.svg`