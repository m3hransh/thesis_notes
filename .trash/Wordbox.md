---
tags: utility
aliases:
---
#  Wordbox

```dataview
TABLE W as Words
FROM !"Bins"
where W != null 
SORT file.mtime DESC
```