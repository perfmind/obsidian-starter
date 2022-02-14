---
creation date: <% tp.file.creation_date() %>
tags: DailyNote 2022
---

<< [[<% tp.date.now("YYYY-MM-DD", -1, tp.file.title, "YYYY-MM-DD") %>]] | [[<% tp.date.now("YYYY-MM-DD", 1, tp.file.title, "YYYY-MM-DD") %>]]>>

## Today's Quote
<% tp.web.daily_quote() %>

## Start of Day
### I am grateful for...

### What would make today great?

### Let's starting up
- [ ] Check Email
- [ ] Check Twist
- [ ] Check Trello
- [ ] Adding additional task if any

## Daily Log
### Github
- [ ] One day one commit 📅 <% tp.date.now("YYYY-MM-DD", 0, tp.file.title, "YYYY-MM-DD") %> 

## End of Day

### Reflection
#### What did I learn?

#### What I am Working on?

#### What I am struggling with?

#### Is there help I can get from others?

### Let's wrapping up
- [ ] Clean Unused Headings in Daily Log
- [ ] Write Reflection
- [ ] Check tomorrow's calendar
- [ ] Adding task for tomorrow

## Meeting Log
### 0000:

## Tasks

### Over Due
```tasks
not done

due before <% tp.date.now("YYYY-MM-DD") %>
```

### Due Today
```tasks

not done

due on <% tp.date.now("YYYY-MM-DD") %>

```

### No Due Date
```tasks

not done

no due date

path includes Daily Note/20

```

### Done Today
```tasks

done on <% tp.date.now("YYYY-MM-DD", 0, tp.file.title, "YYYY-MM-DD") %>

```