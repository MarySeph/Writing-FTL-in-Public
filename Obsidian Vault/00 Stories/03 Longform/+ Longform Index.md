---
tags: x/index
---
up:: [[+ For the Freedom to Love Dashboard|FTL Dashboard]]
# + Longform Index
List all notes in this folder except index itself and subfolder files
```dataview
TABLE status, draft from "Workspaces/00 Stories/03 Longform" and -#x/index and -"Workspaces/00 Stories/03 Longform/50 Archives"
SORT file.name ASC
```

I want to see all file with tag #output/storychapter/draft
```dataview
TABLE status, draft, tags from -#x/index
WHERE status="draft/abandoned"
SORT file.name ASC
```
