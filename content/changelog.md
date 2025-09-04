---
created: 2025-09-03
last-modified: 2025-09-03 17:50:17
aliases:
tags:
description:
draft: false
enableToc: false
enableLocalGraph: true
enableBacklinks: true
"Parent:":
"Children:":
---

# [[content/changelog]]

## Recent Updates

```dataview

TABLE file.folder AS "Folder", dateformat(file.mtime, "dd.MM.yyyy") AS "Last modified" 
FROM "" 
WHERE startswith(file.folder, "content/") OR file.folder = "content"
SORT file.mtime DESC LIMIT 25

```
