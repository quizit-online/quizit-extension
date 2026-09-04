# Quizit - browser extension

Advanced AI assistant for quizzes on educational platforms.
Website: <https://quizit.online>

This repository hosts the **downloadable builds only**. The source lives in a
private repository; every release here is published automatically by its CI.

## Download

[**Download the latest version**](https://github.com/quizit-online/quizit-extension/releases/latest/download/quizit-chrome.zip)

The link above always points at the newest build, so it is safe to bookmark or
share.

## Install (Chrome, Edge, Brave, Opera)

Chrome only installs unpacked extensions from disk, so the zip has to be
extracted first — you cannot drag the zip itself into the browser.

1. Download `quizit-chrome.zip` and **extract it** to a folder you will keep
   (e.g. `Documents/quizit`). Deleting that folder uninstalls the extension.
2. Open `chrome://extensions` (Edge: `edge://extensions`).
3. Turn on **Developer mode** — top-right toggle.
4. Click **Load unpacked** and pick the extracted folder (the one that directly
   contains `manifest.json`).
5. Pin Quizit from the puzzle-piece icon in the toolbar.

Chrome shows a "Disable developer mode extensions" warning on every start-up for
extensions installed this way. That is expected; dismissing it keeps Quizit
enabled.

## Updating

Downloading a build from here does not auto-update. To move to a newer version,
download the new zip, extract it over the same folder (replacing the files), and
press the reload icon on the Quizit card in `chrome://extensions`.

For automatic updates, install from the Chrome Web Store instead:
<https://chromewebstore.google.com/detail/quizitonline/gbihgipgiggdfncfhinohincfbieonkf>

## Support

Questions or a broken solve: <https://quizit.online>
