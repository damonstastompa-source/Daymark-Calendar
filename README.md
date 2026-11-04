# Daymark Calendar — v1.7.0

Offline-first personal calendar and time planner for GitHub Pages.

## Features
- Day, Week, Month, Year, Day Flow, and Agenda views
- Events, all-day events, durations, recurring events, and series exceptions
- Multiple workplaces with independent colors and weekly schedules
- Manual work shifts and per-workplace schedule templates
- Scheduled and actual work times, break duration, and weekly hour summaries
- Overall and per-workplace availability settings
- Day Flow timeline with open-time estimates and commitments
- Agenda lists upcoming events chronologically
- Conflict visibility through the calendar's overlapping event blocks
- Seven themes, adjustable overlay drawer, JSON backup/restore, and printing
- Local browser storage; no account or server required

## Deploy
Upload the five files in this folder to the repository root and enable GitHub Pages from the main branch/root. Open once online to install the service worker; subsequent visits can work offline.

## Data
Events, workplaces, schedules, and availability are stored locally. Use Backup calendar regularly. Backups include both calendar events and Work module data. Restore replaces existing event and workplace data.

## Notes
- Day Flow estimates open time from the gaps between timed events; it does not infer travel time or automatically reserve buffers.
- Actual work hours are optional manual records, not payroll calculations.
- Workplaces can be deactivated without deleting their associated event history.
