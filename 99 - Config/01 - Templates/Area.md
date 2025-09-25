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
LIST rows.file.link
FROM [[]]
FLATTEN area AS groups GROUP BY groups
```
## Material
## Clippings
