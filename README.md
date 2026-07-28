# Time-mile

**[time-mile.com](https://time-mile.com)** — turn your Google Maps Timeline (Location History) into professional CSV, Excel, PDF, or JSON reports. Built for mileage tracking, tax deductions, and business travel reimbursement.

## What it does

Google's Timeline export is a deeply nested JSON file — not something you can open in a spreadsheet. Time-mile parses it in your browser and turns every trip and place visit into a clean, filterable, exportable table.

- **Import** the new Direct Export format (`Timeline.json` from Android/iOS) or the legacy Google Takeout ZIP
- **Filter and sort** by date, activity type, or distance
- **Export** to CSV, Excel-ready format, PDF, or JSON
- **100% local processing** — your location history is parsed entirely in your browser and never uploaded to a server

## Mileage rate guides

Official per-country rates, with sources and verification dates:

- [Export Timeline to Excel](https://time-mile.com/guides/export-timeline-to-excel/) · [Convert Timeline to a mileage log](https://time-mile.com/guides/convert-timeline-to-mileage-log/) · [Timeline missing recent trips](https://time-mile.com/guides/timeline-missing-data/)
- [IRS standard mileage rate](https://time-mile.com/guides/irs-mileage-rate/) (US) · [HMRC approved mileage allowance](https://time-mile.com/guides/hmrc-mileage-allowance/) (UK) · [CRA automobile allowance](https://time-mile.com/guides/cra-mileage-rate/) (CA) · [ATO cents per kilometre](https://time-mile.com/guides/ato-mileage-rate/) (AU)
- [Barème kilométrique](https://time-mile.com/guides/bareme-kilometrique/) (FR) · [Kilometerpauschale](https://time-mile.com/guides/kilometerpauschale/) (DE) · [Kilometervergoeding](https://time-mile.com/guides/kilometervergoeding/) (NL/BE) · [Rimborso chilometrico](https://time-mile.com/guides/rimborso-chilometrico/) (IT) · [Kilometraje](https://time-mile.com/guides/kilometraje/) (ES)
- [Mileage tax deduction explained](https://time-mile.com/guides/mileage-tax-deduction/)

## Tech stack

React + TypeScript + Vite, [Mantine](https://mantine.dev/) UI, Firebase (Auth/Firestore/Analytics/Hosting), Stripe for the premium tier. Static, hand-built marketing pages (English, French, Spanish, German, Italian, Portuguese, Bengali, Indonesian) are built as separate Vite entries alongside the app.

## Source

This repository holds the project description only — the application source is private.

## Privacy

All Timeline processing happens client-side. No location data is ever sent to a server as part of parsing or exporting.
