# Privacy policy

*Version 4 · Effective November 13, 2026*

This policy explains what information the sagitt·AI·re application (the "App") handles, where it is kept, when it leaves your device and what you can do about it. It is part of the terms of use. "Developer" means the developer of sagitt·AI·re.

## 1. In short

The Developer collects nothing. The App has no account, no advertising, no analytics and no tracking, and it sends nothing to the Developer. Your records stay on your device. A photo of the target leaves your device only when you choose to have an end scored by an artificial-intelligence ("AI") service, and then only to that service.

## 2. What the App keeps on your device

To work, the App keeps the following in its private storage on your device:

- your bows (name, type, settings and the description of your arrows) and the places you shoot at, as you name them;
- your sessions: date, place, bow, distance, target face, ends, arrows, scores, and the photo of each end with a small preview;
- your settings, including your scoring method, the AI services you set up, their addresses and models, your look and your archer in game mode, and the date you accepted the terms of use;
- your API keys, encrypted with a key held in the device's secure hardware (Android Keystore).

Other apps cannot read this information, and the photos do not appear in your gallery. The App turns off Android's automatic cloud backup and device-to-device transfer, so none of it is copied off your device automatically.

## 3. When information leaves your device

**Scoring with your own API key.** When an end is scored, the App sends, over an encrypted connection (HTTPS) and only to the AI service you chose, at the address saved with its key:

- the photo of the end, with its hidden data (location, device model, date) removed and, unless you turn this off, cropped to the square around the framing circle, which leaves out most of the surroundings but not what stands in front of the target;
- the setup the service needs to score it: the target face and paper faces, the number of arrows, the scoring rule, your arrow description, and the language for its notes;
- your API key, which identifies your account with that service.

Your name, places, history, scores and details about your device are never sent. The technical details that apps usually send about the device are replaced with "unknown". Like any internet service, the AI service can see your network (IP) address.

**Sharing with your AI app.** The App prepares the photo and a prompt, and you choose the app to share them with, using Android's share sheet. What happens next is between you and that app.

**Manual scoring.** Nothing leaves your device.

**Sharing a session.** When you tap Share on a session, the App prepares a summary (date, bow, place, round, scores and, if you choose, a picture of the scoresheet), and you choose the app to share it with. The photos of your ends are never included.

**Reporting a scoring problem.** When you tap Report a scoring problem on an end, the App writes an email about that end (face, distance, rule, AI model, and each arrow as the AI scored it and as it is now) and, if you tick it, attaches the copy of the photo sent to the AI service. Your email app opens with no recipient: you choose who to send it to, and nothing is sent until you send it. Your bows, places and dates are not included.

**Exports.** When you export your records, the App writes one file, which is not encrypted, where you choose (for example, your Downloads or a cloud drive). Depending on what you choose to export, it holds your bows, places, sessions, ends, arrows and notes, the AI service's answer for each end, your settings other than keys and addresses, and the photos of your ends at full size and uncropped, with anyone or anything that appears in them. API keys and service addresses are never put in an export. Keep the file somewhere private and delete copies you no longer need: anyone with the file can read your records and see your photos.

**Checking a key.** The "Check key" button sends your key to its service to confirm it works.

## 4. AI services

Each AI service you use is a separate company with its own terms and privacy policy, which decide how it uses, keeps and protects what it receives, including whether it may use it to train its models, and where in the world it processes it, which may be outside Québec and Canada. Read them before you use the service, and choose the service and the settings of your account with it accordingly. The Developer has no control over these services and receives nothing from them.

As of November 2026, the services the App offers say this about what they receive through their APIs. Their own terms prevail and may change, and the sagitt·AI·re website lists what each one says:

- they keep it for up to 30 or 55 days, depending on the service, to detect abuse, and some keep it up to 2 years when their safety systems flag it;
- some check images for child sexual abuse material and keep flagged images for review;
- with a paid account, they do not use it to train their models or improve their products, unless you agree to it in your account;
- one service's free tier uses it to improve its products and lets human reviewers read it: with that service, use a key with billing turned on, as the App's Settings explain.

## 5. Permissions

- **Camera**, to photograph the target. Android asks you the first time.
- **Internet**, to reach the AI service you chose. It is not used with manual scoring.

The App asks for no location, contacts, microphone or storage permission. Importing a photo uses Android's photo picker, which gives the App only the photo you pick.

## 6. How long information is kept

Your information stays on your device until you delete it. You can delete an end or a session, delete old full-size photos (Settings → Storage and backup → Free up space), remove a key, or erase all sessions or everything (Settings → Storage and backup → Erase data). Uninstalling the App deletes everything it keeps on your device.

## 7. Your choices and rights

Because the Developer holds no information about you, everything the App knows about you is on your device and under your control: you can see it in the App, take a copy of it with an export, correct it, and delete it, as described above. For information an AI service has received, use the rights its privacy policy gives you; under the laws of Québec and Canada, and the laws where you live, you may have rights of access, correction and deletion with that service.

## 8. Security

The App protects your information with Android's app sandbox, encrypts your API keys, sends scoring requests only over HTTPS, blocks unencrypted connections, and removes hidden data from photos before sending them. No method is completely secure: protect your device with a screen lock, create an API key just for the App with a spending limit, and delete it with its service if your device is lost.

## 9. Children

The App is not directed at children under 14 and collects no information from anyone. AI services set their own minimum ages. A parent or guardian should set up any AI service a child uses, or choose manual scoring, which sends nothing.

## 10. The website

The sagitt·AI·re website (ashencroft-hyperautomation.github.io/sagittaire) is hosted by GitHub. When you visit it, GitHub receives your network (IP) address and the pages you ask for, and handles them under the GitHub Privacy Statement; the Developer does not receive these logs. The website has no account, no cookies, no analytics, no advertising and no tracking. Its fonts and other files are served from the website itself, so in a current browser, visiting it contacts no other service. Your choice of light or dark appearance is remembered by your browser only. If you open an issue on GitHub, what you write is public and handled by GitHub under its own terms.

## 11. Changes to this policy

If this policy changes in substance, the new version will be shown in the App, with its date, and you will be asked to accept the terms of use again before continuing. The current version is always in the App (Settings → About and legal) and on the sagitt·AI·re website.

## 12. Questions

The App and its website are made pro bono for Archery Canada and run by the Developer. For questions about this policy, open an issue at github.com/ashencroft-hyperautomation/ashencroft-hyperautomation.github.io/issues. Issues are public: do not include personal information, photos or API keys.

## 13. Language

This policy is drawn up in French and in English; both versions are equally authoritative. *Cette politique est rédigée en français et en anglais; les deux versions font également foi.*
