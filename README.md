# bowl.

*a tasting menu for an audience of one*

This is the official menu of the restaurant I apparently run now. It operates out of my kitchen, has one table, no phone number, and a single regular who has never once paid a bill.

The menu is live at **[susangadegone.github.io/dogmealmenu](https://susangadegone.github.io/dogmealmenu/)**.

## The concept

We believe in seasonal, locally sourced cuisine. Specifically: whatever season it currently is, sourced locally from my counter the moment I turn my back.

Our patron is a dog. "Food-motivated" doesn't cover it — this is a diner who treats the sound of a cheese drawer opening as a legally binding dinner invitation, who has memorized the acoustic difference between a banana being peeled and a granola bar being unwrapped from two rooms away, and who regards the twice-daily arrival of the exact same kibble with the astonished joy of someone winning the lottery twice.

## Service hours

| Service | Time | Enforcement |
| --- | --- | --- |
| Morning | 7:00 sharp | wet nose, deployed directly to the face |
| Evening | 18:00 precisely | pacing, sighing, formal complaints filed via stare |
| From the Floor | continuous | reflexes I can no longer compete with |

## Selected press

> ★★★★★ — "Inhaled it in nine seconds. No notes."
> — *The Regular*

> ★★★★★ — "The carrot course was an insult. I ate it anyway."
> — *The Regular*

> ★★★★★ — "I have also eaten mulch, so calibrate accordingly."
> — *The Regular, in the interest of transparency*

## The app

bowl. is now a full establishment, not merely a menu. On a phone, open the site, tap share → **Add to Home Screen**, and it installs like a real app — icon, full screen, the works. Front of house includes:

- **Today** — the daily special, rotated nightly by a committee of one algorithm. Everyone in the family sees the same special. The soup is water. The wait is 0 minutes; the party is already at the table.
- **Menu** — the full carte, unchanged, unchanging, rapturously received twice a day.
- **Service** — the official ledger. Mark breakfast and dinner served (finally, an answer to "did anyone feed the dog?"), and record each Cheese Tax as it is levied. Records are kept per device, in the tradition of small establishments with one notebook.
- **Reviews** — the press desk. Request a fresh review from our sole critic at any time. It will be five stars. It is always five stars.
- **Reserve** — a fully functioning reservation system, in the sense that it functions and refuses everyone.

## Frequently asked questions

**Do you take reservations?**
The only table is permanently booked, for the rest of that dog's natural life, and honestly beyond.

**Is the food good?**
Our sole critic once attempted to eat a bee. Their five-star reviews should be read in that light. They are sincere, though. Everything here is sincere.

**Can the menu change?**
The menu changes constantly. The kibble does not. This tension defines the establishment.

## For the humans: deployment

This is a single static page — no build step, no dependencies, just `index.html`.

It deploys to GitHub Pages via the workflow in [`.github/workflows/deploy-pages.yml`](.github/workflows/deploy-pages.yml) on every push to the default branch. If the first run complains that Pages isn't enabled, flip it on once: **Settings → Pages → Source → GitHub Actions**. After that, service resumes automatically, twice daily, forever, exactly like breakfast.
