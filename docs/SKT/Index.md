---
type: index
world: The Forgotten Realms
campaign: "Storm King's Thunder"
date: 12-03-2021
game_date: [1520-04-13]
aliases: [SKT]
---
QuickLinks: [[TODO|Ongoing TODO list]] | [[Dice Roller]] | [[Strokes of Genius]] | [[Data to Link]] | [[House Rules]] | [[Quick Info]]

# Campaign Index


![[Party#Characters]]

## Quests and Questions
- [x] Who is [[The Boy]]?
- [x] What is the Red stone? [[Soul Prism]]
- [x] Save [[Piotyr Bronsson]]
- [ ] Return [[The Boy|Timothy Denovan]] to [[Waterdeep]]
- [x] Who is the masked figure? [[Aadhan Du'Coreiseuse]]
- [x] Retrieve the [[Whetstone of Helm]]
- [ ] Stop the [[The Ordning]]


## Agenda

## Recent [[Sessions]]
```dataview
table title as Title, date as "Date Created", location as "Location"
WHERE type = "session" and session_number != null
and campaign = "Storm King's Thunder"
Sort session_number Desc
limit 3
```

## Utilities
```dataview
table description as "Description"
WHERE type = "utility"
Sort file.name ASC
```

## [[Cities]]
```dataview
table description as "Description" from "/"
WHERE type = "city" and file.name != "City"
and campaign = "Storm King's Thunder"
SORT file.name ASC
```

## [[Factions]]
```dataview
table description as "Description"
where type = "faction" and file.name != "Faction"
Sort file.name ASC
```

## The Adventure
- ### [[Chapter One - New Adventure]]
	- #### [[Part One - Saving Nightstone]]
	- #### [[Part Two - Bronsson Secrets]]
	- #### [[Part Three - Saving Goldenfields]] - You are here.
- ### [[Chapter Two - Discovering Evil]]
	- #### [[Part Four - Du'Coreiseuse Deception]]
	- #### [[Part Five - The Boy]]
	- #### [[Part Six - The Savage Frontier]]
- ### [[Chapter Three - The Savage Frontier]]
	- #### [[Part Seven - Sarhiri Syndicate]]
	- #### [[Part Eight - Dance with Devils]]
	- #### [[Part Nine - The Chosen Path]]
- ### [[Chapter Four - Sleeping Giants' Wake]]
	- #### [[Part Ten - Dens of Giants]]
	- #### [[Part Eleven - Caught in the Tentacles]]
	- #### [[Part Twelve - Doom in the Desert]]