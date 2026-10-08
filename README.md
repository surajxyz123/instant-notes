Instant Notes

An all-in-one Android app built around notes: notes, tasks, reminders, calendar, file manager, gallery, tools, news, a browser, an app store and games, in one APK.

- Package: `com.suraj.instantnotes`
- Latest: **v3.86** (versionCode 121)
- Platform: Android (sideloaded APK)
- Size: about 19.4 MB (20,343,416 bytes)
- SHA-256 (v3.86): `cd48ea34c8fa79e0824557c284a5c970e649ff895ca540c6f6958354efb2726b`

> Personal project, built for one user and shared as-is. It is developed and tested on a computer first, and many features have not yet been confirmed on a real phone. See [Known status](#known-status).

## Features

### Notes
- Full-page editor with a foldable formatting panel
- Rich text: fonts, colours, highlight, checklists, headings, lists, links
- Draw & Paint studio: pens, shapes, stickers, 12 paper templates, and photo/video/audio placed anywhere on the page
- 20 floating sticky-note designs (move, resize, fold, close)
- Voice typing (including Hindi), per-note lock, export to PDF or image
- Labels, archive, reminders and a Calendar tab (day, 3-day, week, month, schedule views; local only, no Google sync)
- App lock with PIN and fingerprint

### Privacy
- Hidden vault for notes, images and video
- Private spaces in the File manager, Gallery and Browser downloads
- Optional intruder photo on wrong PIN or pattern (enable in Settings)

### Files and media
- File manager with multi-select and favourites
- Gallery with text select from images
- Let's Music: offline player with playlists, equalizer, sleep timer and .lrc lyrics

### Tools
Cleaner, OCR, photo editor, habit tracker, PDF scanner, focus timer, calculators and converters, image read-aloud, alarms, smart notes search, ebook reader, code studio, lock camera (record with the screen off), AI Hub, AeroTransfer, Nearby share, Downloader, Study Guard, Fake Call, Decision Spinner, Walkie Talkie, Time Capsule and Compass. Tools can be reordered and given custom gestures in Settings.

### AI Hub
Own chat interface (not a browser) with:
- No-login Quick Chat using free models
- Free-key providers: Gemini, OpenRouter, Groq, Mistral, Cohere, Hugging Face
- Custom API (your own endpoint, model ID and key)
- History, search, pin, personas, compare, export, file attach, voice in and out

You supply your own API keys. They stay on the device.

### News and browser
- Inshorts-style news cards by section, short publisher news videos, Live TV (official free streams only)
- Full browser: tabs, incognito, bookmarks, history, downloads, ad-block, own video player and image viewer

### Instant Store
A built-in store for browsing open-source apps from GitHub, GitLab, Codeberg and F-Droid.

**Free Alternatives** (new in v3.86): 82 hand-picked open-source apps in nine categories, with search and pagination, plus a button for the full F-Droid catalogue.
- Package IDs, summaries and licenses were checked against the official signed F-Droid index
- The shelf does not bundle APK links. Tapping an app resolves it against the signed, device-compatible catalogue, then shows the download details
- Signature and hash checks are shown before download. They are not malware scanning
- Catalogue anti-feature notices (for example NonFreeNet) are displayed
- First sync is about 15 MB
- These are free apps, not a replacement for every paid app. Some have paid extras, online services or need root or a server

No mod, cracked or pirated content is fetched or listed.

### Playtime
Offline games inside the app: Shinobi Royale, Ridgeline Rally, a 15-game mini arcade, Chess, Ludo, Sugar Pop and original action games, with joystick controls and levels.

### Themes
- Morphism themes and glassmorphism themes
- 57 festival and seasonal themes with an optional auto theme that switches ahead of each festival or season
- Theme applies across sections; websites, media, game scenes and the lock camera black screen keep their own colours

## Install

1. Download `Instant-Notes-v3.86.apk` from the Releases page. If a file ends in `.apk.txt`, rename it to `.apk`.
2. Allow installs from your file manager or browser when Android asks.
3. Open the file and tap Install.

**Updating:** install over the existing app. Do not uninstall and do not clear data, or you lose your notes.

All releases are signed with the same certificate, so updates install over each other. Older builds before v3.55 used a different key and need a one-time uninstall (export your data first).

Verify the download:

```
sha256sum Instant-Notes-v3.86.apk
```

It should match the SHA-256 above.

## Known status

The app is tested on a computer, not on a phone, before each release. Reported fixes are often confirmed only after the user tries them. As of v3.86 these are **not yet confirmed on a real phone**:

- Theme showing in Playtime, Files, Tools and Gallery
- Short news videos
- Private video playback and move-in/move-out in the secret space
- Instant Store providers and the Free Alternatives shelf
- Festival themes and auto switch
- Fake Call (ringing outside the app, custom audio)
- Walkie Talkie, Nearby share, Downloader
- Study Guard closed-eye detection
- Gesture reliability, lock camera volume keys, AI Hub, intruder photo, Calendar

If something fails, please open an issue with your Android version, the app version and a screenshot or screen recording.

## Limits

- Online features (news, Live TV, AI Hub, Store, Downloader) need internet
- The Downloader does not support YouTube, Instagram, Facebook, TikTok, DRM or pirated sites
- Nearby share and Walkie Talkie depend on your phone's Wi-Fi hardware and range
- No VPN is included

## Privacy

Notes, vault and settings are stored on the device. The app has no account system. Network requests go only to the services you use (news, Store sources, AI providers you configure, web pages you open).

## Build and signing

Source is kept privately. Signing keys and backups are never published. Releases are verified with APK signature scheme v2/v3.

## License

No license has been chosen yet. Until one is added, all rights are reserved. Add a `LICENSE` file before accepting contributions..
