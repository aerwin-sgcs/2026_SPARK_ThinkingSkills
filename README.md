# SPARK Stretch Thinking

A single-page web app of **30 open-ended thinking prompts** for gifted learners in Years 6–10. Students choose a task, write a response in the browser, and can export their work as PDF or JSON. Responses are auto-saved silently to the student's own browser — nothing is shared, nothing leaves the device.

The tasks are organised into five sections — Inquiry & Investigation, Problem Solving & Design, Language & Communication, Ethics & Philosophy, and Creative & Imaginative — and are aligned to James Anderson's *Learnership* framework (Mindset Continuum, Habits of Mind, the Agile Learner, Effective Effort).

## Files in this repo

- **`index.html`** — the app itself. Open it in any modern browser, or use the GitHub Pages link.
- **`habits-of-mind.html`** — companion reference page mapping each task to the framework, including a 30-row Habits of Mind table.

## For students using the app

1. Pick a task from the left sidebar.
2. Type your response in the writing area. It saves automatically as you type.
3. When done, you can:
   - **Download PDF** — your response for the current task.
   - **Prepare screenshot** — a tidy panel you can screenshot for sharing.
   - **Download all responses** — every task with a written response, in one PDF.
   - **Backup (JSON)** — a full backup of all your responses; keep this somewhere safe before changing browsers or clearing data.
   - **Clear all my work** — wipes everything from this browser. Two confirmations required.

## For maintainers

To add or edit tasks: open `index.html`, find the `TASKS` array near the top of the `<script>` block, and add or modify entries. The sidebar grouping, task counter, and PDF exports all update automatically.

To update the live site: edit the file in this folder, then **Commit to main** and **Push origin** via GitHub Desktop. GitHub Pages rebuilds within ~60 seconds.

## Privacy

All student data is stored in the browser's `localStorage`. Nothing is sent to any server. The JSON backup and PDF downloads are generated locally and stay on the student's device unless they choose to share them.

## Framework reference

For the full task-by-task alignment to Anderson's *Learnership* — including narrative sections on the Mindset Continuum, the Agile Learner, Effective Effort, and a 30-row Habits of Mind mapping — see [`habits-of-mind.html`](habits-of-mind.html).
