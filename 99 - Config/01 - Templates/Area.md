---
tags:
  - area
date: "{{date}}"
aliases:
---
# Linked Projects
```dataview
LIST
FROM #project
WHERE area = [[]]
SORT file.ctime ASC
```
# Resources
## Notes
```dataview
LIST
FROM [[]]
WHERE !contains(tags, "project")
```
## Material
## Clippings
