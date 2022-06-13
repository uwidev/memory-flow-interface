---
alias: 
tags: tool, suggestion
---
# Organizing Tasks With Tags
Tags can be leveraged to organize [[Tasks]].

For example, if a task relates to art, you can add the `#art` tag to it, and then you can filter specifically for tasks for art.

**Task**
- [ ] #task Draw something cool today #art

**Raw Query**
> \`\`\`tasks
> not done
> description includes #art
> \`\`\`

**Running Query**
```tasks
not done
description includes #art
```

You can also have this query on some [[Dashboard|Dashboard]] ([[02 🎨 Arts Dashboard]]) if it's important.