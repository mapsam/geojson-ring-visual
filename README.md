# GeoJSON Ring Visualization

This page visualizes polygon rings and array order according to the GeoJSON specification. You can view it here.

GeoJSON polygons are comprised of a series of rings, which are arrays of points (latitude & longitude pairs) like `[100.1, 2.0]`. Polygons typically have a single ring that represents the entity entirely. 

Some polygons, though, have interior rings, which render as *holes* (like a donut). In GeoJSON, these interior rings come after the first, exterior ring, in the array order.

