# Business Clock

A simple, self-contained weekly time tracker for reporting worked hours to a supervisor.

## What it does

Business Clock is a personal "punch clock" for tracking how much time you spend
on work tasks and turning it into a clean weekly report for your supervisor.

You describe the task you're about to do, then use **Start**, **Pause**, and
**Stop** to time it — like a stopwatch that remembers what each session was for.
Every completed session is saved with its description, start/end times, and the
worked duration (break/pause time is automatically excluded).

The app then organizes those sessions **by day and by week** (Monday–Sunday) and
adds up your totals. Because it only shows the days and weeks you actually
worked, occasional or part-time schedules are reported accurately — there are no
empty rows for days off. When it's time to report, you export the week you're
viewing as either a **printable PDF timesheet** or a **CSV spreadsheet**, both
showing what you did and how long it took.

Everything runs in a single HTML file and stores data locally in your browser,
so it works offline and keeps your records private — no accounts, servers, or
internet connection involved.

## Usage

Open `index.html` in any web browser (double-click it). No installation, server, or internet connection required.

1. Type what you're working on in the task box.
2. Press **Start** to begin the timer.
3. **Pause / Resume** for breaks; **Stop & Save** when the task is done.
4. Each saved session is grouped by day and week automatically.
5. Use **Print / PDF Report** or **Export CSV** to produce a report for your supervisor.

## Features

- Start / Pause / Resume / Stop timer with a per-task description
- Automatic weekly (ISO week, Monday–Sunday) and daily grouping
- Only weeks/days you actually worked are shown — gaps handled correctly
- Per-day and per-week totals
- Edit or delete entries, or add sessions manually (for forgotten time)
- **Print/PDF report**: clean, supervisor-ready weekly timesheet
- **CSV export**: opens in Excel / Google Sheets
- Your name (click the top-right label) appears on exported reports
- All data stored locally in the browser (localStorage) — private, offline

## Notes

- Data lives in your browser's local storage. Clearing browser data or using a
  different browser/device starts fresh. Export regularly to keep records.
- Closing the tab while a timer is running will prompt a warning.
