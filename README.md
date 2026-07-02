# Time-mile

**[time-mile.com](https://time-mile.com)** — turn your Google Maps Timeline (Location History) into professional CSV, Excel, PDF, or JSON reports. Built for mileage tracking, tax deductions, and business travel reimbursement.

## What it does

Google's Timeline export is a deeply nested JSON file — not something you can open in a spreadsheet. Time-mile parses it in your browser and turns every trip and place visit into a clean, filterable, exportable table.

- **Import** the new Direct Export format (`Timeline.json` from Android/iOS) or the legacy Google Takeout ZIP
- **Filter and sort** by date, activity type, or distance
- **Export** to CSV, Excel-ready format, PDF, or JSON
- **100% local processing** — your location history is parsed entirely in your browser and never uploaded to a server

Guides: [exporting Timeline to Excel](https://time-mile.com/guides/export-timeline-to-excel/) · [mileage tax deductions](https://time-mile.com/guides/mileage-tax-deduction/) · [Timeline missing recent trips](https://time-mile.com/guides/timeline-missing-data/)

## Tech stack

React + TypeScript + Vite, [Mantine](https://mantine.dev/) UI, Firebase (Auth/Firestore/Analytics/Hosting), Stripe for the premium tier. Static, hand-built marketing pages (English, French, Spanish, German, Italian, Portuguese, Bengali, Indonesian) are built as separate Vite entries alongside the app.

## Development

```bash
npm install
npm run start:dev   # local dev server
npm run build        # production build (tsc + vite build)
```

## Privacy

All Timeline processing happens client-side. No location data is ever sent to a server as part of parsing or exporting.
