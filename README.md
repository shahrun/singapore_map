### singapore_map

#Convert geojson to mbtiles(base + forest)

tippecanoe input.geojson -o output.mbtiles --drop-densest-as-needed --extend-zooms-if-still-dropping 
