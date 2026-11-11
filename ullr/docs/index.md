---
title: Ullr — archery records with AI scoring
hide:
  - navigation
  - toc
---

<div class="hero" markdown>
![Ullr, archery records with AI scoring: the carved target icon, the name, and two phone screens showing the dashboard and an end with two arrows to check.](images/banner.png)
</div>

# Ullr

**Your archery scoresheet, kept for you.** After each end, take a photo of the target. An AI finds your arrows and scores them, and circles the ones it isn't sure about. You check those before you pull your arrows, and every session is saved on your phone with its photos.

*Named after Ullr, the Norse god of archery.*

<div class="grid cards" markdown>

-   :material-camera-outline: **Photo, then score**

    ---

    One photo per end. Each arrow gets its ring, X to M, on every World Archery face, including two 3-spot faces at once.

-   :material-target: **Uncertain arrows circled**

    ---

    Arrows close to a line are circled in amber. Tap one, pick the right ring, confirm. The line rule applies: touching the 9 line is a 9.

-   :material-chart-bar: **Your history**

    ---

    Dashboard, every past session, a scoresheet and a score-by-end chart. Each end keeps its photo.

-   :material-shield-lock-outline: **Your phone, your data**

    ---

    Records stay on the phone. Only the photo of the target is sent, and only to be scored. No account, no ads, no tracking.

</div>

## See it

<div class="shots" markdown>
<figure markdown>
![Review of an end: markers on six arrows on two triple faces, two of them circled in amber.](images/screenshots/review-check.png){ .shot }
<figcaption>Two arrows to check, circled in amber</figcaption>
</figure>
<figure markdown>
![A flagged arrow selected: the AI's two candidate rings, 9 and 10, highlighted with its confidence.](images/screenshots/review-select.png){ .shot }
<figcaption>One tap to pick the right ring</figcaption>
</figure>
<figure markdown>
![Session summary with total 1084, a bar chart of end totals and the scoresheet.](images/screenshots/session.png){ .shot }
<figcaption>Session summary and scoresheet</figcaption>
</figure>
<figure markdown>
![Dashboard with sessions, average per arrow, best total, X count and recent sessions.](images/screenshots/dashboard.png){ .shot }
<figcaption>Dashboard</figcaption>
</figure>
<figure markdown>
![History: sessions grouped by month, with a filter by bow.](images/screenshots/history.png){ .shot }
<figcaption>Every past session</figcaption>
</figure>
<figure markdown>
![Settings: scoring method and the choice of AI service.](images/screenshots/settings.png){ .shot }
<figcaption>Your choice of AI</figcaption>
</figure>
</div>

[All screenshots](screenshots.md){ .md-button } [How it works](how-it-works.md){ .md-button }

## What it does

| | |
|---|---|
| **Any session** | Place, date, bow type (traditional, recurve, olympic, compound) and bow, distance, target face, number of paper faces, any number of arrows per end. |
| **Your scoring rule** | X = 10, inner 10 only (World Archery compound) or X = 11, chosen per session, with a default in Settings. Change it later and every total is recalculated. |
| **The AI service of your choice** | Anthropic (Claude), Google (Gemini) or OpenAI, with your own API key. All three get the same instructions. |
| **Works at the range** | No signal? Photos are saved and scored when the phone is back online. You can always score an end by hand. |
| **Bows** | Several bows, with a catalog of current compound bows (PSE, Hoyt, Mathews, Bowtech), draw weight and draw length. |
| **English and French** | The whole app follows your phone's language. |

## Status

Ullr is a personal project, in active development. It runs on Android 8 and later. **It isn't on Google Play yet.** See the [roadmap](roadmap.md) for what's done and what's next.
