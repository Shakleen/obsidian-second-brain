---
created: <% tp.file.creation_date("YYYY-MM-DD HH:mm") %>
modified: <% tp.file.last_modified_date("YYYY-MM-DD HH:mm") %>
tags:
  - weekly
  - journal
hubs:
  - "[[journal]]"
  - "[[hubs/weekly|weekly]]"
---

# <% tp.file.title %>

## Goals
- [ ] 

## Comments

---
*Last week: [[<% tp.date.now("gggg-[W]ww", -7) %>]]*
*Next week: [[<% tp.date.now("gggg-[W]ww", 7) %>]]*
*This month: [[<% tp.date.now("YYYY-MM") %>]]*