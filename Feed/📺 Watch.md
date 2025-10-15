# 📺 Watch

If you want to subscribe to the Youtube Channel do so here 
Latest published videos 

```dataview 
TABLE WITHOUT ID dataCover AS "Cover", link(file.path, title) AS "Post", description AS "Description", date AS "Published"
FROM ""
WHERE type = "video"
SORT date DESC
LIMIT 30
```