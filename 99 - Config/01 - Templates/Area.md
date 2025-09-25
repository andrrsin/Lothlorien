---
tags:
  - area
date: "{{date}}"
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
WHERE !contains(tags, "project") or !contains(tags, "project")
```
## Material
## Clippings
