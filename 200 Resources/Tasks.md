---
alias: Tasks
tags: tool, suggestion
---
# Tasks
**Problem**: I have things I need to do inside this vault, but can't quite get to. I can't figure out how to organize it well.

**Tasks** are checklist, but with extended functionality through the Obsidian [Tasks](obsidian://show-plugin?id=obsidian-tasks-plugin) plugin. Example below.

- [ ] #task Come back home with milk for the kids

They utilize [[Tags|Tagging]] to mark the checklist as a task. Tagging is also used to [[Organizing Tasks With Tags|Organize Tasks]].

Tasks are useful when you have need to plan or defer work to the future. They're also handy for [[Projects|Projects]] and ensuring errands are visible during [[Alignment|Alignment]].

## How to Task
Tasks are created by adding the #task tag to any checklist item. 

Where you create them is up to you. You may find it practical adding tasks in-line during a [[Rambling|Ramble]], or you might find it better to have a centralized place to hold all tasks. For the latter, you can aggregate tasks through queries (see below).

## Queries
You can then query for tags using code blocks.

**Raw Query**
> \`\`\`tasks
> not done
> \`\`\`

**Running Query**
```tasks
not done
```

You should have the query on some [[Dashboard|Dashboard]] note, like [[01 🏠 Main Dashboard|🏠 Main Dashboard]].

Be sure to check out the [Tasks plugin](obsidian://show-plugin?id=obsidian-tasks-plugin) for full details.