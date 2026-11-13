# Team Tracker

A single-page tool for a team lead to track daily attendance (office / WFH / leave), platform hours and tasks completed against each member's targets, with an automatic weekly report.

## Features
- Daily roster: mark Office, WFH or Leave and enter platform hours and tasks done
- Summary cards: in office, WFH, on leave, not marked, and how many met target
- Per-member targets for hours and tasks (a day counts as met only when both are reached; task target 0 = not tracked)
- Weekly report (Mon–Sun): daily hours/tasks, totals, days target met, average hours, leave days
- Data is saved in the browser (localStorage). When opened as a Claude artifact it also syncs across devices; on GitHub Pages it stays in that browser only

## Run
Open `index.html` in a browser. No build step or dependencies.

## Host on GitHub Pages
Repo Settings → Pages → Deploy from branch → `main` / root.
