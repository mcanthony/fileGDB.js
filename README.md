fileGDB.js
==========
Implementing [this amazing reverse engineering](http://trac.osgeo.org/gdal/wiki/FGDBSpecification) by [rouault](https://github.com/rouault) in JavaScript

Produces valid geojson but the location values are screwy, this  seems to be an upstream  issue as the python one has the same problem.

Ccurrently only works in node
though that's just because I haven’t ran it through browserify.  main function takes two buffers
one for the .table the other for the corresponding  .tablex. 