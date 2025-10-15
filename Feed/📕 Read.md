# 📕 Read

Latest Blog Post 

```dataview 
TABLE WITHOUT ID dataCover AS "Cover", link(file.path, title) AS "Post", description AS "Description", date AS "Published"
FROM ""
WHERE type = "blog"
SORT date DESC
LIMIT 30
```

