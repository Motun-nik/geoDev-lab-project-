
# Data notes

## Osogbo LGA Boundary
- Location: Osogbo, Osun State, Nigeria
- LGA code: 30030
- Source: Nigeria administrative boundaries
- Selected LGA feature: 1
- Geometry: Polygon
- CRS: EPSG:4326 - WGS 84

## OSM roads, extracted via QuickOSM
- Query: highway=*
- Area: Osogbo LGA extent
- Extracted and clipped to Osogbo LGA boundary
- Features: 4,965
- Geometry: Line (MultiLineString)
- CRS: EPSG:4326 - WGS 84
- Columns observed: fid, full_id, osm_id, osm_type, highway, name
- NULL values: Present in the name field
- Coverage: To be confirmed by visual inspection

## OSM buildings, extracted via QuickOSM
- Query: building=*
- Area: Osogbo LGA extent
- Extracted and clipped to Osogbo LGA boundary
- Features: 68,996
- Geometry: Polygon (MultiPolygon)
- CRS: EPSG:4326 - WGS 84
- Columns observed: fid, full_id, osm_id, osm_type, building
- NULL values: Present in several attribute fields
- Coverage: To be confirmed by visual inspection
