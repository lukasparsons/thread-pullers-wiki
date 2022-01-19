---
type: index
world: The Forgotten Realms
campaign: "Khan"
date: 12-09-2021
aliases: [RoT]
---
QuickLinks: [[RoT Party]]

# Campaign Index


![[RoT Party#Characters]]

## Quests and Questions
- [ ] Oof


## Agenda

## Sessions
```dataview
table date as "Date Created", location as "Location"
WHERE type = "session" and session_number != null
and campaign = "Khan"
Sort session_number ASC
```

## [[Cities]]
```dataview
table description as "Description" from "/"
WHERE type = "city" and file.name != "City"
and campaign = "Khan"
SORT file.name ASC
```