# Cron Expression Explainer

This tool reads a standard five-field cron expression, minute, hour, day of month, month, and day of week, and explains it in plain English, field by field and as one sentence. It supports stars, steps, ranges, lists, and named months and weekdays.

**Live demo:** https://0xelitesystem.github.io/cron-expression-explainer/

## What it does

Paste a five-field cron expression. The tool breaks it into its five fields, explains each one in words, and assembles a single plain-English sentence describing when the job runs. It flags a field that is not valid and a wrong number of fields. Quick-fill chips load common schedules.

Schedulers vary in their extensions, so the reading is for the standard five-field form. Confirm against the exact scheduler you use before relying on it.

## Aesthetic

A perpetual almanac: a parchment page with a gold rule, a moon-phase crest, a serif title, and the expression read out like an entry in an old calendar.

## Privacy

Everything runs in your browser. Nothing you type is sent anywhere, stored, or saved. Closing the tab clears it.

## Use it

Open `index.html` in any modern browser, or host it as a static page. No build step, no dependencies, no network calls.

## License

MIT. Copyright (c) 2026 0xelitesystem.
