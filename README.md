# Mind Map Scheduler

Plan projects and ideas as a mind map. Break them into tasks, set start and due dates, assign people or teams, attach screenshots and files, and tick tasks off as you go.

**Open the app:** https://dilfadzree98.github.io/mindmap-scheduler/

## Install it like an app

Open the link in **Chrome** or **Edge** and click **Install app** in the top bar, or use the install icon at the right end of the address bar. It gets its own window and a Start-menu icon, and works offline after the first visit.

## Your data stays on your device

Your maps and attachments are saved in your own browser on your own computer. Nothing is uploaded, and other people can't see your map.

- **Back up or move your map:** click **Export** to save a `.json` file, which includes attachments. Use **Import** on another browser or computer to load it.
- **A report people can read:** click **Report** (top bar for everything, or in the side panel for one project) and pick **Excel** (a .xlsx with a Summary and a Tasks sheet) or **PDF** (the print window opens: choose *Save as PDF*).
- **Share a single project:** select it and click **Export** in the side panel. The other person imports it and chooses **Add to my map**.

## Features

- Mind-map canvas: drag, zoom, auto-arrange, and fold branches
- Projects, ideas and tasks, with progress bars
- Move a task (with its sub-tasks) to another parent: drag its card onto the new parent, or press M / click **Move** and pick from a searchable list
- Duplicate an item with everything under it (D, or **Duplicate** in the side panel), e.g. to reuse a project as a template: the copy starts with nothing ticked, and picking a new first date moves all its dates
- Start and due dates, overdue highlighting, and an agenda grouped by day
- Timeline view (T): a bar from start to due date for every dated task, grouped by project, with a line for today. Drag a bar to move it, or drag its ends to change the dates
- Month calendar (C): every dated item on its day, overdue ones in red. Drag an item to another day to move it (its sub-tasks and the tasks waiting for it follow along); on a phone, tap a day to see its list
- Completion dates, plus a remark when closing an item that still has open sub-tasks
- Checklists inside a task: small tick-box steps in the side panel, a "2/5" count on the card, and the steps can be ticked right on the card
- Task dependencies: a task can wait for others (**Waits for** in the side panel). The timeline draws arrows between them, waiting cards show a lock, and moving a task later pushes the tasks waiting for it later too
- Priority flags (High, Medium, Low) with keys 1, 2, 3, plus an agenda filter and "High first" sorting
- Recurring tasks (daily, weekly, monthly): ticking one done adds the next one automatically
- Reminders: a pop-up when you open the app lists what is due today or overdue (click the red "overdue" count to see it again), optional Windows notifications, and a nudge to back up after 7 days of changes
- Calendar file: **Report → Calendar** saves unfinished items with dates as an .ics file for Google Calendar, Outlook or your phone, with a reminder the day before (works even when the app is closed)
- Teams and people: assign tasks to a person or a whole team, and filter the agenda by either
- Attachments: paste screenshots with Ctrl+V, or drag files onto a card
- Works on phones: compact toolbar with a More menu, panels that slide up from the bottom, pinch to zoom, and press-and-hold to add an idea or rename a card
- Undo/redo, search, and light/dark theme

It's a single HTML file with no build step: `index.html` is the whole app.
