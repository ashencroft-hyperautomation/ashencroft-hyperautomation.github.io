# Privacy

Short version: **your records stay on your phone.** Only the photo of the target leaves it, and only to be scored, by the AI service you chose.

## What stays on your phone

Your sessions, scores, places, bows and photos are kept in Ullr's private storage on the phone.

- Other apps can't read them, and the photos are not in your gallery.
- Nothing goes to a cloud backup or to a new phone automatically.
- There's no account, no advertising, no analytics and no tracking.
- **Uninstalling the app deletes everything.** Export is coming (see the [roadmap](roadmap.md)), so keep the app installed until then.

## What is sent, and when

Only when an end is scored with an AI service, over an encrypted connection, to that service only:

- **the photo of the end**, without hidden data (no location, no phone model) and, by default, trimmed to the target area;
- **your setup**: target face, paper faces, number of arrows and scoring rule, and your arrow description;
- **your API key**, which identifies your account with that service.

**Never sent:** your name, your places, your history, your scores, or details about your phone. The technical information that apps usually send about the phone (Android version, processor) is replaced with "unknown".

![The privacy section of Settings: the switch to send only the target area, and the list of what is sent and never sent.](images/screenshots/settings-privacy.png){ .shot width="240" }

Settings shows the same list, under **What is sent to …**, for the service you chose.

## What each service does with it

| Service | Used to train AI? | Kept |
|---------|-------------------|------|
| **Anthropic** | No | Under Anthropic's commercial terms |
| **OpenAI** | No, unless you opt in on your account | Ullr asks OpenAI not to store the request. Safety logs are kept up to 30 days. |
| **Google Gemini**, with billing on | No | Logged for a limited time for abuse detection |
| **Google Gemini**, free tier | **Yes**: may be used to improve Google's products, and read by human reviewers | Not stated |

!!! warning "Gemini: use a key with billing on"
    On Google's free tier, your target photos may be used by Google and seen by reviewers. Use a key from a Google Cloud project with billing turned on. Ullr can't check this for you.

With the **Claude app** method, the trimmed photo and the prompt go through your own Claude account, and stay in that conversation like any other chat.

## Your API key

- It's stored encrypted on the phone, never shown again, and never put in an export.
- It's only sent to the service it belongs to.
- **Remove key** in Settings deletes it.

Create a key just for Ullr and set a spending limit with the service. If you lose your phone, delete the key there.

## Permissions

| Permission | Why |
|------------|-----|
| Camera | To photograph the target, asked the first time |
| Internet | For scoring with an AI service |

No location, contacts, microphone or storage permissions. Importing a photo uses Android's photo picker, which only gives Ullr the photo you choose.
