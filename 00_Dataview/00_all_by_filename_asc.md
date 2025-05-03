ノート一覧（名前・作成日時・更新日時、ファイル名順）
``` dataview
TABLE
    choice(length(aliases) > 0, aliases[0], file.name) AS "ノート名",
    dateformat(file.ctime, "yyyy-MM-dd, HH:mm") AS "作成日時",
    dateformat(file.mtime, "yyyy-MM-dd, HH:mm") AS "更新日時"
FROM ""
SORT file.name ASC
```