---
tags: []
aliases: 
UID: <% tp.date.now("YYYY-MM-DDTHH-mm-ss") %>
---
<%*
const uid = tp.date.now("YYYY-MM-DDTHH-mm-ss"); // UID形式のファイル名（
await tp.file.move(`${uid}`); // Vaultのルート直下にファイルを移動
%>
