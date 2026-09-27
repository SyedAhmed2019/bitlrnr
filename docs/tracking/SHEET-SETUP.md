# BitLrnr progress tracker — Google Sheet setup

Spreadsheet: https://docs.google.com/spreadsheets/d/1NlJI9oz3bfAtnEgEAc1h81Xwmo5Es5obYOh2arTP6b0/edit

The Cursor browser is not signed into your Google account, so import the CSV files from this folder manually (about 5 minutes).

## Tab 1: `Master Steps`

1. In Google Sheets, add a sheet named **Master Steps**.
2. **File → Import → Upload** → choose `master-steps.csv`.
3. Import location: **Replace current sheet** (or insert new sheet).
4. Separator: **Comma**. Convert text to numbers: **Yes**.

## Tab 2: `Daily Schedule`

1. Add a sheet named **Daily Schedule**.
2. Import `daily-schedule.csv` the same way.

## Tab 3: `Daily Log` (optional)

Create columns:

| Date | Planned Step ID | What I did | Status | Blockers | Tomorrow |

Use this for free-form notes; keep **Daily Schedule** `Status` in sync (`Planned` → `In Progress` → `Done` → `Skipped`).

## Conditional formatting (recommended)

- **Status** column on Daily Schedule:
  - Done = green
  - In Progress = yellow
  - Planned = gray
  - Skipped = orange

## Filter views

- Filter **Week** = current week for your 1–2 hour focus.
- Filter **Phase** to see all Content vs Editor tasks.

## Sync from repo

After edits in Git, re-import CSVs or copy new rows from:

- `docs/tracking/master-steps.csv`
- `docs/tracking/daily-schedule.csv`
