```dataview
TABLE status as "وضعیت", priority as "اولویت"
FROM "02 System Architecture"
WHERE file.name != this.file.name
SORT priority desc
```
