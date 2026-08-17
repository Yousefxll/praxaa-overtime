# Praxaa — Overtime Justification

A nursing overtime justification model: it compares the hours a unit **requires**
against the hours it can actually **cover**, and states whether the overtime worked
is justified.

**Live:** https://yousefxll.github.io/praxaa-overtime/

## What it does

- Three staffing methods — **Fixed** headcount, **Ratio** (acuity-weighted), **HPPD**
- Two absence methods — deduct actual leave days, or apply a calculated **relief factor**
  (the model prevents double counting)
- Working days from a real calendar: weekly rest day + a public-holidays list
  (holidays falling on the rest day are never double-counted)
- Editable units database — add, rename and delete units
- A **single-page A4 print sheet** for signing off
- CSV export

Everything runs in the browser. No server, no network calls — fonts and icons are
embedded, so it works offline. Your edits are saved per-device in the browser.

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole application — self-contained |

---

© 2026 Yousef Alhasan. All rights reserved.
Proprietary — no use, copy, modification, or distribution without written permission.
