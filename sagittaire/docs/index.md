---
title: sagitt·AI·re — archery records with AI scoring
hide:
  - navigation
  - toc
---

<div class="hero" markdown>
![sagitt·AI·re, archery records with AI scoring: the icon, half a World Archery target and half a white maple leaf on Archery Canada red, the name, and two phone screens showing the dashboard and an end with two arrows to check.](images/banner.png)
</div>

# sagitt·AI·re

**Your archery scoresheet, kept for you.** After each end, take a photo of the target. An AI finds your arrows and scores them, and circles the ones it isn't sure about. Or skip the AI and tap your arrows on the photo yourself. Every session is saved on your phone with its photos.

*Its name: Sagittaire, French for Sagittarius, the archer among the stars, with AI at its heart.*

**sagitt·AI·re is Archery Canada’s app**, created pro bono by Ashencroft Studio. It is for practice and leisure: its scores are never official, and in competition only the official scorecards count.

<div class="game-band" markdown>

## Or play it like a game { #game-band }

Turn on **game mode** and sagitt·AI·re becomes a small pixel-art video game. Your archer walks around a Norse hall and an archery range: the **bow rack** opens your bows, the **shooting line** starts a session, the **hearth** shows your statistics. Same records, same scoring: only real shooting earns anything.

<div class="shots" markdown>
<figure markdown>
![The range in pixel art: three target butts, the shooting line with lanes 1 to 3, the arrow stand, trees, and a fox following the archer.](images/screenshots/game-range.png){ .shot }
<figcaption><b>Walk to the range</b> and shoot</figcaption>
</figure>
<figure markdown>
![The hall: the archer with red braids, a flower crown and a fur mantle walks past the rug with a fox beside them.](images/screenshots/game-pet.png){ .shot }
<figcaption><b>Dress your archer</b>, pick a companion</figcaption>
</figure>
<figure markdown>
![Trophies: level and experience, ten badges with gold medals, personal bests.](images/screenshots/game-trophies.png){ .shot }
<figcaption><b>Levels, badges</b>, a weekly challenge</figcaption>
</figure>
</div>

![The four legendary archers from the front, side and back: Artemis with her hound, Ullr with a raven, Robin Hood with a fox, and Hou Yi.](images/game-legends.png){ .pixel width="360" }

Outfits and hall decorations to earn, an owl for four weeks in a row, a war horn for a personal best, the range in four seasons, music and sounds made for sagitt·AI·re.

[Discover game mode](game.md){ .md-button .md-button--primary }

</div>

## Two ways to use it

Same records, same scoring: pick the one you like, and switch at any time in **Settings → Appearance and game**.

<div class="grid cards" markdown>

-   :material-view-dashboard-outline: **Normal mode**

    ---

    ![The dashboard: sessions, average per arrow, best total, X count and recent sessions.](images/screenshots/dashboard.png){ .shot width="200" }

    A clear app with tabs: Dashboard, History, Bows, Stats and Settings. Quick at the range.

    [Normal mode](normal.md)

-   :material-gamepad-variant-outline: **Game mode**

    ---

    ![The hall in pixel art, with the fire, the bow rack, the trophy wall, the mirror and the desk.](images/screenshots/game-hall.png){ .shot width="200" }

    Who wants to find their way through text menus? Walk your archer around a Norse hall and a range: the bow rack opens your bows, the shooting line starts a session. Pixel art, music, a companion.

    [Game mode](game.md)

</div>

## Three ways to score

<div class="grid cards" markdown>

-   :material-key-outline: **Your own API key**

    ---

    Automatic. Each photo is scored in the background by the AI service you choose, with your own key: a major service, or any OpenAI-compatible service at the address you give.

    [Your own API key](scoring-api.md)

-   :material-share-variant-outline: **Share with your AI app**

    ---

    No key. Share the photo and a ready-made prompt with the AI app already on your phone, then paste its answer back.

    [Share with your AI app](scoring-share.md)

-   :material-gesture-tap: **Manual**

    ---

    No AI, nothing sent. Tap each arrow on the photo and pick its ring, or skip the photo and tap the scores.

    [Manual scoring](scoring-manual.md)

</div>

[Compare the three](scoring.md){ .md-button }

## Features

<div class="grid cards" markdown>

-   :material-camera-outline: **[Sessions](sessions.md)**

    ---

    Place, discipline, bow, distance, face and arrows per end. One photo per end, even with no signal. Personal bests per round, and a summary to share.

-   :material-target: **[Checking arrows](review.md)**

    ---

    Uncertain arrows circled in amber. Tap one, pick the right ring. The line rule applies.

-   :material-scale-balance: **[Scoring rules](rules.md)**

    ---

    X = 10, inner 10 only or X = 11, per session. Change it later and every total is recalculated.

-   :material-bow-arrow: **[Bows](bows.md)**

    ---

    All your bows, drawn as their type, with a catalog of current compound bows.

-   :material-chart-bar: **[Statistics](stats.md)**

    ---

    Every session with its photos, a score-by-end chart, trends, consistency, where your arrows group and a heat map per spot, by distance and face.

-   :material-archive-outline: **[Storage and backup](backup.md)**

    ---

    Export to one file, restore on a new phone, free up space from old photos.

-   :material-palette-outline: **[Look and language](look.md)**

    ---

    Three themes, including one for bright sunlight. English, French, German and Spanish.

-   :material-shield-lock-outline: **[Privacy](privacy.md)**

    ---

    Records stay on the phone. No account, no ads, no tracking. Nothing is removed without asking.

</div>

[All screenshots](screenshots.md){ .md-button } [How it works](how-it-works.md){ .md-button } [Getting started](guide.md){ .md-button .md-button--primary }

## Status

sagitt·AI·re is a pro bono project of Ashencroft Studio, in active development. It runs on Android 8 and later. **It isn't on Google Play:** it is installed directly on the phone. See the [roadmap](roadmap.md) for what's done and what's next. Using sagitt·AI·re means accepting its [terms of use](terms.md): it is provided as is. Its [privacy policy](privacy-policy.md) explains what stays on your phone and what is sent.

Every genuine copy is signed with the same certificate, whose SHA-256 fingerprint is `338111aa561dbb1493daf046ad0df6be70c0d313d941654768d6891daafb94a7`. The app shows its own in **Settings → About and legal**; to check an APK file before installing it, run `apksigner verify --print-certs` (Android SDK build tools) on it and compare the *certificate SHA-256 digest*.
