# Daymark Calendar — v1.2.0

A static, offline-ready calendar designed for GitHub Pages.

## Features
- Day, week, month, and year views
- Create, edit, and delete events
- Recurring events: daily, weekly, every 2 weeks, monthly, yearly, and custom day intervals
- Optional recurrence end date or occurrence count
- Recurring-series changes/deletions: this occurrence, this and future occurrences, or entire series
- Event fields: date, title, time, category, location, notes
- Color-coded categories: Appointment, Meeting, Bill, Birthday, Personal
- Seven themes: High Contrast, Moonlight, Ocean, Blacklight, Ember, Sunrise, Sunset
- Overlay menu drawer, closed by default, with adjustable opacity in Settings
- Dedicated Settings screen for appearance
- JSON backup and restore
- Click a date in month view to open its day view
- Print the currently selected view
- Local browser storage; no account or server required
- Service worker caches the app for offline use after its first successful online load

## GitHub Pages
1. Create a repository.
2. Upload the four files in this folder to the repository root.
3. In **Settings → Pages**, deploy from your main branch and root (`/`).
4. Open the published site once while online. Then it can load offline from that browser/device.

## Data & privacy
Events and preferences are stored in this browser's local storage. They do not automatically sync between devices or browsers. Use **Backup calendar** to export a JSON file and keep it somewhere safe. Restore replaces the current event list.

## Notes
- Browser storage can be cleared by device/browser cleanup. Keep backups.
- Offline availability requires the app to be loaded once over HTTPS first.
- Printing uses the browser's print dialog; choose landscape for month/week layouts if desired.
