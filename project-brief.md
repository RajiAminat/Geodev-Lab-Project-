# My project brief

## The question
Where are the gaps in access to improved water points (boreholes, wells, public taps) in Abeokuta South Local Government Area, Ogun State, relative to where people actually live?

## Why it matters
Water-point mapping is a direct entry point into hydrology and environmental work — this brief is the foundation for later work on groundwater recharge or watershed analysis around Abeokuta South. An LGA planning officer or WASH NGO could use the output to prioritize new boreholes in wards where population is dense but water-point coverage is thin.

## Study area
Abeokuta South Local Government Area, Ogun State, Nigeria.

## The data I need
- Ward boundaries — GRID3 Ogun Operational Ward Boundaries — https://grid3.gov.ng/dataset/ogun-operational-ward-boundaries — GeoJSON
- LGA boundary — GRID3 Ogun Local Government Administrative Boundaries — https://grid3.gov.ng/dataset/ogun-local-government-administrative-boundaries — GeoJSON
- Water points (wells, taps, drinking water) — OpenStreetMap via HOTOSM Nigeria Points of Interest export — https://data.humdata.org/dataset/hotosm_nga_points_of_interest — filter to `man_made=water_well`, `man_made=water_tap`, `amenity=drinking_water`, clipped to Abeokuta South
- Population — WorldPop Nigeria population counts, UN-adjusted, 100 m resolution — https://data.humdata.org/dataset/worldpop-population-counts-for-nigeria — GeoTIFF, most recent year

## What I would build
A map showing distance-to-nearest-water-point overlaid on population density, highlighting wards where high population sits far from any mapped water point. Longer term, an updatable version an LGA WASH officer could rerun whenever new OSM edits or population estimates become available.
