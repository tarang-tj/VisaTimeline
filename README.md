# VisaTimeline

A single-page web app that turns your visa's key dates into a personalized list of immigration deadlines and exports them to your calendar.

Live: https://tarang-tj.github.io/VisaTimeline/

## What it does

1. Pick your status: F-1 Student, OPT / STEM OPT, H-1B Worker, H-4 Dependent, or J-1 Exchange Visitor.
2. Enter your key dates (program end, EAD start/end, H-1B start/end, and so on).
3. Get a generated timeline of the relevant milestones for that status: application windows, grace periods, extension windows, and reminders like SEVIS registration, I-94 verification, and AR-11 address reporting.
4. Export the timeline as an `.ics` file or add events to Google Calendar.

## Stack

Plain HTML, CSS, and vanilla JavaScript in a single `index.html`. No frameworks, no build step, no dependencies. Calendar export builds a standard iCalendar (`.ics`) file in the browser.

## Run it

Open `index.html` in a browser, or use the live link above. To serve locally:

```bash
python3 -m http.server 8080
```

Then visit http://localhost:8080.

## Note

This is an informational planning tool, not legal advice. Confirm your actual dates and requirements against your official documents (I-20, EAD, I-797) and USCIS guidance.
