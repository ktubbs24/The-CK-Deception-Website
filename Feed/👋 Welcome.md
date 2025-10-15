
# 👋 Welcome
---
```dataview 
TABLE WITHOUT ID dataCover AS "Cover", link(file.path, title) AS "Post", description AS "Description", date AS "Published"
FROM ""
WHERE contains(featured, true) OR featured = true
SORT date DESC
LIMIT 12
```



