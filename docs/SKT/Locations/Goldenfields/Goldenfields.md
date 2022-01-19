---
type: city
world: The Forgotten Realms
campaign: "Storm King's Thunder"
description: Huge, walled temple-farm dedicated to [[Chauntea]].
date: 12-03-2021
aliases: [The Granary of the North]
---

Main: [[Index|SKT]]
Related [[Cities]]


# Goldenfields

###### Flavor Text: 
*Goldenfields is a huge, walled temple-farm dedicated to [[Chauntea]], the goddess of agriculture. Called “the Granary of the North,” it’s the only reason many Northerners ever taste soft-fleshed fruit larger than bush berries. Waterdeep and its neighbors consume the temple’s reliable output: carefully husbanded grains and dried, oil-packed, or salted foodstuffs preserved in vast storage cellars, vats and squat stone grain-towers.*

##### Quick Notes:
[[Goldenfields Index]] is useful for quickly navigating Goldenfields.

---

### [[People]]

```dataview
table description as "Description"
Where type = "npc" and contains(location, "Goldenfields")
Sort file.name ASC

```

---

### [[Places]]
``` dataview
table description as "Description"
Where type = "place" and contains(location, "Goldenfields")
Sort file.name ASC
```

---
### Shops
``` dataview
table description as "Description"
Where type = "shop" and contains(location, "Goldenfields")
Sort file.name ASC
```
---
### Events
```dataview
table description as "Description"
Where type = "event" and contains(location, "Goldenfields")
Sort file.name ASC
```

---

Factions:
- [[Emerald Enclave]]
- [[Zhentarim]]
- [[Lords' Alliance]]


---

## Goldenfields Map
```leaflet
id: [goldenfields-map]
image: [[goldenfields-1.png]]
height:500px
lat:50
long:50
minZoom:5
maxZoom10
defaultZoom:6
unit:feet
scale:1
darkMode:false
```

---

## Notes:
 More than 5,000 people live and work in Goldenfields year round, farming more than twenty square miles of tillage in gangs of hard-working gardeners.
 
 The sprawling temple-farm is built on higher groudn than the surrounding fields, and it's enclosed on all sides by a wall of mortared stone. The outer wall is 60 feet high (20 feet high inside the compound) and 30 feet wide. The wall is built out on several points, spaced at least a mile apart, with stone pagodas and barracks at those locations. These watch posts have unobstructed views of the surrounding countryside.
 
 The outer wall is in need of repair in many places. Time and weather have eroded some of the mortar, creating ruts between the stones that can serve as handholds and footholds. Scaling the walls requires a successful DC 15 Strength (Athletics) check.
 
 The entrance to Goldenfields is a large stone gatehouse set into the middle of the south wall. Beyond its gates, dirt roads crisscross the interior of the compound, providing passage between and through its fields and orchards. Roads also run along the inside of the wall, connecting the various watch posts. During the harvest season, wagons make their way between the fields, gathering food and grain and transporting it to cellars beneath the watch posts, where the food is kept under lock and key until caravans from Waterdeep and other settlements arrive to pick it up. In addition to the large grain fields, fruit orchards, and vegetable gardens, smaller gardens hug the outer walls. These gardens grow berries, rhubarb plants, and other such fare.

Most of Goldenfields’ workers live in a small town situated near the abbey, where the abbot hosts morning, noon, and evening prayer. North of town is an enormous inn called Northfurrow's End. Visitors planning to spend the night in Goldenfields are directed here.


#city