# AI in L&D 2026: Benchmark Yourself

A single-page quiz that lets anyone answer the five closed-choice questions from the *AI in L&D 2026: Around the Core* survey, then see exactly how their answers compare with the published 2026 results.

Source report: *AI in L&D 2026: Around the Core* by Donald H Taylor and Eglė Vinauskaitė (531 respondents, 55 countries, surveyed 25 June to 6 September 2026).

## What it does

- Walks through the survey's five closed-choice questions (the free-text and consent/demographic questions aren't included, there's nothing to benchmark against).
- Lets the visitor answer as "my team or department" (matching the original survey's wording) or "just me," and rewrites the relevant answer options into first person accordingly.
- Question 3 only appears if the visitor says they work on a workplace L&D team, matching how the original survey handled it, and carries a bold note on who it applies to.
- Results screen shows every answer against the published 2026 benchmark as a bar chart, scaled to the highest answer within each question, with your own picks in bold purple.
- A closing "So, Where Do You Stand?" card pulls the five answers together into one practical read: a strength and a thing worth watching.
- A "Copy my results" button builds a plain-text version of the whole comparison for pasting into Slack, email, and so on.

## A note on the figures

Most of the benchmark numbers are the report's own published percentages. A handful weren't printed anywhere and were measured directly from the published charts; these are marked with a tilde (`~`). One figure (Q4's "Other") was too small to measure reliably and has no printed number to fall back on, so it's shown as a range rather than a false-precision point estimate. Question 3 (department change)'s figures are recalculated from the report's own published counts to show each option's share of respondents, since the report's printed percentages for that question use a different base (share of all selections made, not share of respondents).

## Running it

There's no build step. Open `index.html` directly in a browser, or serve the folder with anything that serves static files.

## Hosting

This repo is set up to be served directly by GitHub Pages from the root of the `main` branch.

## Status

This is an independent, unofficial companion to the report. It isn't produced by, endorsed by, or affiliated with the report's authors.

Developed by Pablo Alvarez.
