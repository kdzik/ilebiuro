# Ile biuro

A simple calculator for hybrid work: how many days you still need to be in the office this month.

**Open the app:** https://kdzik.github.io/ilebiuro/

## What it does

- Calculates required office days as a percentage of working days, a number per month, or a number per week. Results always round up.
- Takes Polish public holidays and vacation into account.
- Supports required weekdays, e.g. "2 days on Monday or Friday".
- Lets you mark office days and vacation in a calendar.

## How it works

A single static page with no build step, no libraries and no external requests. Your data is stored only in your browser (`localStorage`) and is never sent anywhere. It can be installed on a phone as a PWA and works offline.

## License

MIT
