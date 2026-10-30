# Ile biuro

A simple calculator for hybrid work: how many days you still need to be in the office this month.

## What it does

- Calculates required office days as a percentage of working days, a number per month, or a number per week. Results always round up.
- Takes Polish public holidays, vacation and sick leave into account.
- Supports required weekdays, e.g. "2 days on Monday or Friday".
- Lets you mark days in a calendar and keeps a monthly history.

## How it works

A single static page with no build step, no libraries and no external requests. Your data is stored only in your browser (`localStorage`) and is never sent anywhere. It can be installed on a phone as a PWA and works offline.

## License

MIT
