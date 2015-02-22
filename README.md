nz_urban_areas_geojson
============================

Census Urban Area boundaries as used by Statistics New Zealand, converted to GeoJSON

## Licencing

This work is based on/includes [Statistics New Zealand](http://www.stats.govt.nz/)'s data which are
licensed by Statistics New Zealand for re-use under the [Creative Commons Attribution 3.0 New Zealand
licence](http://creativecommons.org/licenses/by/3.0/nz/).

Source ESRI shapefiles are available on the [Statistics NZ
website](http://www.stats.govt.nz/browse_for_stats/people_and_communities/Geographic-areas/digital-boundary-files.aspx).

### Special note about this dataset

Urban areas also include a layer with the ID of 502, which is the shape
of all non-urban rural areas. This geojson file exceeds the 100mb Github
file limit, and for this reason has been excluded.


### Use with Bower:

Add the following to your bower.json:

```
"nz_urban_areas_geojson": "git://github.com/nzherald/nz_urban_areas_geojson#1.0.0"
```

#### Use with bower-rails:

Add the following to your Bowerfile:

```
asset 'nz_urban_areas_geojson', '1.0.0', github: 'nzherald/nz_urban_areas_geojson'
```

### Contributing

Feel free to fork and send pull requests, or open issues if you run into
any mistakes.
