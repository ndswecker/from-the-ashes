# Creatures Index

This index updates automatically in Obsidian with the Dataview plugin.  
Any file in **05 - Creatures** with the tag `monster` in its YAML frontmatter will appear here.

---

## All Creatures

```dataview
TABLE cr as "CR", type as "Type", alignment as "Alignment"
FROM "05 - Creatures"
WHERE contains(file.tags, "monster")
```

