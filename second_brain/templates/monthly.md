---
created: <% tp.file.creation_date("YYYY-MM-DD HH:mm") %>
modified: <% tp.file.last_modified_date("YYYY-MM-DD HH:mm") %>
tags:
  - monthly
  - journal
hubs:
  - "[[journal]]"
  - "[[hubs/monthly|monthly]]"
---

# <% tp.file.title %>

## Goals
- [ ] 

## Comments

---
*Last month: [[<% tp.date.now("YYYY-MM", "P-1M") %>]]*
*Next month: [[<% tp.date.now("YYYY-MM", "P+1M") %>]]*