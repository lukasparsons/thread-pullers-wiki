---
type: index
description: This is a list of all monsters I have added and used in the campaign
aliases: []
tags: []
date: 12-06-2021
---
Main: [[Index|SKT]]
# Monsters Index
## All Monsters 
*That I have added so far...*
```dataview
table description as "Description", ddb as "DDB"
where contains(type, "monster") and file.name != "Monster"
sort file.name asc
```

## Giants
*That I have added so far...*
```dataview
table description as "Description", ddb as "DDB"
where contains(type, "monster") and contains(type, "giant")
sort file.name asc
```


## Goblinoids
```dataview
table description as "Description", ddb as "DDB"
where contains(type, "monster") and contains(type, "goblinoid")
sort file.name asc
```
