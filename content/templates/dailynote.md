---
tags: dailynote
---
# [[<% tp.file.title %>]]
<% await tp.file.move("/people/"+tp.file.title) %>

## Meetings

```dataview
TABLE summary as "Summary" from [[<% tp.file.title %>]]
where contains(type,"meeting")
sort date desc
```