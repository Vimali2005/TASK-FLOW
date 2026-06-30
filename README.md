# TaskFlow — Personal Task Manager

A lightweight, no-dependency task manager built with vanilla HTML, CSS, and JavaScript. Add tasks, tag them by category, mark them done, filter the list, and keep track of progress — all in the browser, no backend required.

👩‍💻 **Built by:** [Vimali K](https://github.com/Vimali2005)

---

## Features

- **Add tasks** with a single input + Enter key support
- **Categorize** tasks as Work, Personal, or Study
- **Mark complete** with a single click — completed tasks get a strikethrough and fade
- **Delete tasks** instantly
- **Filter view** by All / Active / Done / category
- **Live counters** for total and completed tasks
- Clean dark, editor-inspired UI with smooth transitions

## Tech Stack

- HTML5
- CSS3 (custom properties, flexbox, grid)
- Vanilla JavaScript (DOM manipulation, event delegation, array methods — no frameworks)

## How It Works

Tasks are stored in a JavaScript array in memory and re-rendered on every change. The app uses:
- **Event delegation** on the task list for handling checkbox and delete clicks efficiently
- **Array filter methods** to power the All/Active/Done/category views
- **Dynamic DOM updates** to keep the UI in sync with state without a page reload

## Run It Locally

No build tools or installs needed — just open the file in a browser:

```bash
git clone https://github.com/Vimali2005/Vimali2005.github.io.git
cd Vimali2005.github.io
open taskflow.html   # or double-click the file
```

## What I Learned

This project was built to apply core JavaScript concepts — state management, event handling, and array filtering — on top of existing HTML/CSS skills, as a step toward more dynamic, interactive web applications.

## Future Improvements

- [ ] Persist tasks with `localStorage` so they survive a page refresh
- [ ] Add due dates and sorting by priority
- [ ] Drag-and-drop reordering
- [ ] Light/dark theme toggle

---

*Part of [my portfolio](../index.html) — a project by Vimali K.*
