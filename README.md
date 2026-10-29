# Overdue

A todo list that doesn't let late tasks fade into the background.

**Try it:** [kdanieldann.github.io/overdue](https://kdanieldann.github.io/overdue/)

- Add tasks with a due date, tick them off, filter by open or overdue
- Overdue tasks get harder to ignore the longer they wait:
  - 1–6 days late: a light tint
  - 7–29 days: a stronger one
  - 30+ days: the whole row goes dark

Everything is stored in your browser (localStorage). No account, no server. "Reset demo data" brings back the sample list.

## Run locally

It's one HTML file. Open `index.html`, or serve the folder:

```
python3 -m http.server
```

Built with Claude Code.
