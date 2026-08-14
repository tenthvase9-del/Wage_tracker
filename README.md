# WageTracker

A tip and wage tracking app for hospitality workers. Track daily card tips, cash tips, and cash paid in. The app calculates how much the house owes you and helps track monthly payments.

## Features

- **Daily entry** — Card tips, cash tips, cash paid in, day-off toggle, notes
- **"You are owed"** — Card tips + cash paid in (what the house owes you)
- **Monthly summaries** — Card tips, cash tips, total tips, cash paid in
- **Mark month as paid** — Track how much you were actually paid and any shortfall
- **Year view** — Browse all months, see tips/owed/paid/short at a glance
- **Dashboard** — All-time stats: total tips, average per month, best/worst month
- **Swipe-to-delete** — Delete entries with undo support
- **CSV export/import** — Export monthly data or import previously exported CSV
- **Auto backup** — Daily JSON backup to app storage
- **Manual backup/restore** — Save and restore from JSON files
- **Dark mode** — Configurable in settings
- **Daily reminder** — Notification to log tips (configurable time)
- **Home screen widget** — Shows current month's owed amount
- **Share month** — Share a formatted summary of any month

## Screenshots

| Main screen | Year view | Dashboard |
|------------ |-----------|-----------|
| ![Main](docs/screenshots/main.png) | ![Year](docs/screenshots/year.png) | ![Dashboard](docs/screenshots/dashboard.png) |

## Tech Stack

- **Kotlin** — Primary language
- **XML + ViewBinding** — UI toolkit
- **SharedPreferences + Gson** — Local data persistence
- **RecyclerView** — Lists
- **JUnit 4** — Unit testing
- Min SDK 24 · Target SDK 36

## Build

```bash
./gradlew assembleDebug      # Debug build
./gradlew assembleRelease    # Release build
```

## Releases

Download the latest APK from [GitHub Releases](https://github.com/Tenthvase9/WageTracker/releases).

## License

MIT
