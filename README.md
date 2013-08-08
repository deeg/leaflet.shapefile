leaflet.shapefile
=================

requires [shapefile-js](https://github.com/calvinmetcalf/shapefile-js) plus if you want it
to be done in a worker, you'll need [catiline](https://github.com/calvinmetcalf/catiline).

usage:

```javascript
new L.Shapefile(arrayBuffer or url[,options]);

L.shapefile(arrayBuffer or url[,options]);
```

options are passed to L.Geojson as is first argument is either an array buffer of a zipped shapefile,
the url to a zipped shapefile, or the url of the file.shp (this assumes file.dbf exists).