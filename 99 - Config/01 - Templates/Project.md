---
tags:
  - project
date: "{{date}}"
area:
---
# A AREA Project
## TODO
- [ ] todo

## Related Resources
```dataview
LIST rows.file.link
FROM [[]] OR outgoing([[]])
WHERE !contains(tags, "area")
FLATTEN area AS groups GROUP BY groups

```



