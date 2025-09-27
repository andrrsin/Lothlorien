---
tags:
  - project
date: "{{date}}"
area:
isFinished: true
---

## TODO

## Related Resources
```dataview
LIST rows.file.link
FROM [[]] OR outgoing([[]])
WHERE !contains(tags, "area")
FLATTEN area AS groups GROUP BY groups

```



