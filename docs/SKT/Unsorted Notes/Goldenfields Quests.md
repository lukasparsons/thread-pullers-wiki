---
type: quest
description: Goldenfields Quest Index
aliases: []
tags: []
date: 12-06-2021
---
Main: [[Index|SKT]]
Related: [[Giants Attack Goldenfields]] | [[Goldenfields]]
# Goldenfields Quests
``` dataview
table description as "Description", giver as "Giver"
where type = "quest" and contains(location, "Goldenfields")
sort file.name asc
```