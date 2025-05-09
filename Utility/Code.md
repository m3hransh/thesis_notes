---
tags: utility
---

# [[ Seedbox]]
##  Backlog
```dataview
TABLE priority FROM "Notes" AND #project OR ("Notes" AND #component)
WHERE status = "backlog"  
SORT file.mtime DESC
```
## 勒 Inprogress

```dataview
TABLE priority FROM "Notes" AND  #project OR ("Notes" AND #component)
WHERE status = "inprogress"
SORT file.mtime DESC
```
##  Completed
```dataview
TABLE priority FROM "Notes" AND #project OR ("Notes" AND #component)
WHERE status = "completed"
SORT file.mtime DESC
```

## Metadata
- Related: [[ Home]]
