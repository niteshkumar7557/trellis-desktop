# Trellis for Mac

Downloads of the Trellis desktop app. Trellis itself is at
**https://trellis.niteshkumar.xyz**: a study map that shows what to study next, what you
can skip, and the earlier topic that's really why you're stuck.

The app opens Trellis in its own window and adds a menu, a menu-bar icon, a daily study
reminder, a shortcut that works from any app (**⌃⌥T**: Control + Option + T), and Google
sign-in through your own browser.

This repository holds only the releases. The source code is private.

## Install

**Needs a Mac with Apple Silicon** (M1 or newer) and an internet connection.

1. Open [**Releases**](../../releases/latest) and download `Trellis-<version>-arm64.dmg`.
2. Open the `.dmg` and drag **Trellis** onto **Applications**.
3. Open Trellis from Applications. The first time, macOS says it can't verify the app.
   Click **Done** (not "Move to Bin"), then open **System Settings → Privacy & Security**,
   scroll down, and click **Open Anyway** next to the message about Trellis. You only do
   this once.

**Why step 3:** removing it needs Apple's Developer Program ($99 a year) to notarize the
app. Trellis is a free student project, so the app is signed without an Apple certificate
("ad-hoc"). That signature proves the app hasn't been changed since it was built, but
not who built it, and macOS asks you to confirm once.

## Updates

Trellis checks this page once a day (and from **Trellis → Check for Updates…**). When a
new version is out it tells you; download it and drag it into Applications again to
replace the old one.

## Privacy

The app stores only its window position and your reminder setting on your Mac. Your
account and study record live on the Trellis server, as on the website.
