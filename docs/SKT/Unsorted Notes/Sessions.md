---
type: index
description: This is a list of all sessions in the campaign so far.
aliases: []
tags: []
date: 12-15-2021
---
Main: [[Index|SKT]]
Related: [[]]
# Sessions
This is a dataview of all the sessions for quick access.

```dataview
table date as "Created", title as "Title"
where type = "session" and campaign = "Storm King's Thunder"
sort session_number desc
```