---
aliases: ['join lines together vim']
created: '<%+ tp.file.creation_date("YYYY-MMM-DD HH:mm") %>'
date updated: '<%+ tp.file.last_modified_date("YYYY-MMM-DD HH:mm:ss") %>'
noteStatus:

---

---

[[vim knowledge|vim know-how]] | [[Vim basics]] | [[Vim Command]]

---

```toc
style: number
```

---

# <%+ tp.file.title %>

---

## what does [[`J` command vim]]

`J` → `join`

It joins lines below the current one together.

`````ad-note
At the 'end' of each line, by default it will append a *space*. 

If a space is already present, it will *not* add another.  
After a 'period' → '.' it will add *2 spaces*.
`````

### Examples

- `3J` → `join the next 3 lines together`

## Join without spaces

- `gJ` → `join without space`

### example

- `3gJ` → join the next 3 lines without putting a space between them



