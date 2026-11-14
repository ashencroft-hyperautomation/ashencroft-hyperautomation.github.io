# Privacy, sovereignty and responsible AI

sagitt·AI·re puts an AI to work for archers, not the other way round. This page says what that means in practice: your records stay yours, you choose who sees a photo (or nobody does), and the AI only ever suggests.

## In short

- **Your records live on your phone.** No account, no server of ours, no advertising, no analytics, no tracking.
- **You choose the AI, or none.** Your own key with the service you pick, your own AI app, or scoring by hand with nothing sent.
- **The AI suggests; you decide.** Every arrow is shown for checking before it counts, and doubtful ones are circled.
- **Built to be checked.** From now on, prompt changes are measured on real labelled photos before they ship.

## Privacy: your records stay yours

- Bows, places, sessions, photos and scores are kept in the app's private storage on your phone. Other apps can't read them, and they're not in your gallery.
- There is no account and no server of ours: the developer receives nothing from the app.
- Nothing is copied to a cloud backup or a new phone automatically. You decide when to export, and where the file goes.
- When an end is scored by an AI service, only what it needs leaves the phone: the photo **cropped to the target** (a setting, on by default) with its **hidden data removed** (location, phone model, date), your round's setup, and your key. Your name, places, history and scores are never sent. Details: [Privacy](privacy.md) and the [privacy policy](privacy-policy.md).

## Sovereignty: you stay in control

- **Choose your service.** Pick the AI service you trust and use your own key, so the account, the bill and the terms are yours, not ours.
- **Choose where it runs.** An OpenAI-compatible service at an address you enter can be one you host yourself or one in the region you prefer.
- **Or no AI at all.** Manual scoring works fully: tap your arrows on the photo or type the scores. Nothing leaves the phone.
- **No lock-in.** An export is one file in open formats (JSON records and JPEG photos) that you keep, restore on another phone, or read with other tools.
- **No dependence on us.** The app needs no server of ours to work, today or later.

## Responsible AI: the archer decides

- **Suggestions, never official.** sagitt·AI·re is for practice and leisure; in competition only the judges' scorecards count.
- **Every arrow is checked.** Scores count only once you confirm the end. Arrows the AI is unsure about (close to a line, partly hidden, blurred) are circled, with the ring on the other side of the line ready to pick.
- **The line rule, as a judge applies it.** A shaft touching a line scores the higher ring; the AI is asked to look at the edge of the shaft, from where it enters the face.
- **It tells you when something is off.** If the photo doesn't show the face you set, the app says so and lets you fix the face.
- **Measured, not guessed.** From now on, changes to the AI's instructions are tested on real labelled photos (exact rings, missed doubts, arrows circled) and ship only if they do better.
- **Mindful of cost.** One request per end, a photo cropped to the target, no hidden extra calls.

## Security

- Your API key is encrypted with a key held in the phone's secure hardware, never shown again, and never put in an export.
- Requests go over HTTPS only, to the address saved with the key; the app doesn't follow redirects elsewhere.
- More: [Security](security.md).

## For everyone

- Four languages: English, French, German and Spanish.
- Screen-reader labels, large touch targets, and charts checked for colour-blind readers.
- Not directed at children under 14. A parent can choose manual scoring, which sends nothing.

## Limits we're honest about

- An AI can be wrong, especially at steep angles, in glare, or with crowded arrows. That's why you check every end.
- An AI service you choose handles the photo under its own terms. Read them, and pick the service and settings that suit you.

## Questions

Ask on [GitHub issues](https://github.com/ashencroft-hyperautomation/ashencroft-hyperautomation.github.io/issues). Issues are public: don't include personal information, photos or API keys.
