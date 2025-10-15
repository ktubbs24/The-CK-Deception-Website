# 🎧 Listen


Latest Podcast Episodes

```dataview 
TABLE WITHOUT ID dataCover AS "Cover", link(file.path, title) AS "Post", description AS "Description", date AS "Published"
FROM ""
WHERE type = "podcast"
SORT date DESC
LIMIT 30
```


