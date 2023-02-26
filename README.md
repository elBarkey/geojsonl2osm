geojsonl2osm
============

This is a fork from [geojsontoosm](https://github.com/tyrasd/geojsontoosm)
Converts Newline-delimited [GeoJSON](http://www.geojson.org/) to [OSM](http://openstreetmap.org) [data](http://wiki.openstreetmap.org/wiki/OSM_XML).

Usage
-----

* as a **command line tool**:
  
        $ npm install -g geojsonl2osm
        $ geojsonl2osm file.geojsonl > file.osm
  
* as a **nodejs library**:
  
        $ npm install geojsontoosm
  
        var geojsontoosm = require('geojsontoosm');
        geojsontoosm(geojson_data);
