# Car Maintenance Log

A self-contained web app (`index.html`) for tracking repairs and maintenance on all your vehicles.
No install, no account, no server needed. Open `index.html` in a browser, or host it on GitHub Pages.

## Features
- **Multiple cars**: year/make/model, nickname, VIN, plate, photo, odometer, oil spec
- **Dated service records**: date, odometer, type of work, shop or DIY, cost, parts, notes
- **Receipts**: attach photos or PDFs to any record; view them in the app, open them in a new tab, or download them
- **Oil change tracking**: the next change is calculated from your schedule (miles and/or months, whichever comes first). After logging one, you can add the next change to your calendar (.ics) or print a windshield sticker
- **Reminders for any service**: set a "next due" mileage or date on any record (tire rotations, brake fluid, etc.)
- **Garage overview**: shows what is due soon or overdue across all your cars
- **Search & filter** by type, year and keyword; spending totals per car and per year
- **Backup**: export or import everything (receipts included) as one JSON file; export CSV per car

## Your data
Everything is stored in your browser's IndexedDB on the device you use. Export a backup from the ⋯ menu
now and then, and import it to move your log to another device.

**Live site:** https://paxman06.github.io/Test-App/
