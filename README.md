# Praxaa — Overtime Justification

A nursing overtime justification model: it compares the hours a unit **requires**
against the hours it can actually **cover**, and states whether the overtime worked
is justified.

**Live:** https://yousefxll.github.io/praxaa-overtime/

## What it does

- One verdict per unit and one for the whole hospital: **required** vs **available**
  hours, the deficit, and how much of the overtime filled it
- Four unit types, each asking only for its own fields:
  - **Ward · 24 h ratio** — beds × occupancy ÷ ratio (+ critical tier), team leader, RACE
  - **Fixed headcount · 24 h** — day and night staff
  - **Shift rota (A/B/C)** — staff per shift on regular days and on the rest day
  - **Daytime unit** — opening hours, a short day, overlapping shifts, closed on holidays
- Monthly entry: occupancy, current staff, overtime and absence by type (hours)
- Contract hours worked out from the calendar: hours per week, rest day and
  public holidays (date ranges, saved holiday names)
- Units can be reported together (e.g. IV Team with the IV Therapy Unit)
- CSV export of the hospital summary, print-friendly layout

Everything runs in the browser. No server, no network calls — fonts and icons are
embedded, so it works offline. Your edits are saved per-device in the browser.

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole application — self-contained |

---

© 2026 Yousef Alhasan. All rights reserved.
Proprietary — no use, copy, modification, or distribution without written permission.
