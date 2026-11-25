# LabKit — Your Blood Test, In Plain Words

LabKit turns a confusing blood-test report into plain words: what each number means, whether it is low, in range, high or worth watching, and what to ask your doctor. Everything stays on your device — no account, no uploads.

**Live:** https://abhiramunni.github.io/labkit/

## What it does

- **Check a number** — pick one of 16 common tests (HbA1c, fasting sugar, cholesterol, LDL, HDL, triglycerides, haemoglobin, Vitamin D, B12, TSH, creatinine, SGPT, platelets, WBC, uric acid, ferritin), type the value exactly as printed, and get a plain-words verdict with a range bar and a question to ask your doctor. Reference ranges are standard adult ranges used by Indian labs, and adjust by sex where it matters.
- **My reports** — save reports (date, lab, test values) on-device. The latest report card shows the 8 headline numbers with verdict pills; tap any report for a full detail sheet with range bars.
- **Trends** — pick a test and see your values across saved reports on a canvas chart with the normal band shaded, plus a "what changed since last time" comparison.
- **Before the test** — an 8-item night-before checklist (fasting, water, alcohol, morning slot, old reports, medicines, workout, sleeve) with a progress ring, plus a countdown to the next booked test.
- **Questions for your doctor** — auto-built from the flagged numbers in your latest report, copy-ready, plus a full plain-text summary copy.
- **Guides** — six short explainers: fasting, why ranges differ by lab, HbA1c vs fasting sugar, reading cholesterol, thyroid in 60 seconds, when to repeat a test.
- Cinematic intro (tap to skip, quick on return visits), 3-step onboarding tour, remove-samples and two-tap erase-all.

## Seed data (clearly marked, removable)

- Full Body Checkup, Thyrocare, 18 Nov 2026 — 12 tests, 6 flagged (HbA1c 5.8% watch, total cholesterol 210 high, LDL 132 high, HDL 38 low, haemoglobin 13.2 low, Vitamin D 18 low).
- Basic Health Check, Apollo Diagnostics, 12 Aug 2026 — 7 tests, 2 watch (LDL 118, Vitamin D 22).
- Next test booked: 28 Nov 2026, 8:00 AM, Thyrocare BTM Layout.

## Important

LabKit explains. It does not diagnose. Reference ranges are standard adult Indian-lab ranges, labelled indicative — the range printed on your own report is the one that counts. Always discuss results with your doctor, and seek urgent care for severe symptoms.

## Tech

Single self-contained `index.html` (no backend, no signup, localStorage only). Warm editorial palette (ivory paper, espresso ink, bronze/amber/terracotta), Fraunces + Inter, two AI-generated warm-editorial photos with slow Ken Burns drift. The published file on GitHub Pages uses the two photos as separate repo-root `.webp` files; the local build embeds them as base64.

## Files

- `index.html` — the app (published version references `labkit-hero.webp` and `labkit-flatlay.webp`)
- `labkit-hero.webp`, `labkit-flatlay.webp` — photos
- `README.md` — this file
- `LICENSE` — MIT
