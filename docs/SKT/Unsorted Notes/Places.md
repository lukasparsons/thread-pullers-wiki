Main: [[Index|SKT]]

# Places (by city)

## Goldenfields Locations
```dataview
table description as "Description"
where type = "place" and contains(locations, Goldenfields)
and file.name != "Place"
sort file.name asc
```