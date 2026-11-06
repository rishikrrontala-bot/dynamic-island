# Dynamic Island for Mac

A free Mac app that turns the notch into a small live screen: music, AirPods,
a shelf for files, a focus timer and your battery, right by the camera.

**[Download it here →](https://rishikrrontala-bot.github.io/dynamic-island/)**

Or grab `Dynamic-Island.zip` straight from the
[latest release](https://github.com/rishikrrontala-bot/dynamic-island/releases/latest).

## Install

1. Download `Dynamic-Island.zip`. Safari usually unzips it for you.
2. Drag **Dynamic Island** into **Applications**.
3. Open it. macOS says it can't verify the app, so click **Done**.
4. Open **System Settings → Privacy & Security**, scroll to **Security** and
   click **Open Anyway**, then **Open Anyway** again and enter your password.
   On macOS 13 or 14 you can Control-click the app and choose **Open** instead.
5. Allow Bluetooth so AirPods banners work.

The app is signed by its builder but not notarized by Apple yet, which is why
macOS asks once. Each release lists the ZIP's SHA-256 so you can check it with
`shasum -a 256 ~/Downloads/Dynamic-Island.zip`.

## What it needs

- A Mac with Apple silicon, on macOS 13 Ventura or later
- Made for MacBooks with a notch; on other displays it drops down from the top
  center and opens from the menu bar icon

## What it does and doesn't do

It uses public macOS features only and stays on your Mac. The one network
request is Spotify album art, loaded from Spotify's own image server. It doesn't
replace the volume and brightness pop-ups, show notifications, or change AirPods
noise control, because macOS has no public way to do those.

Built by Rishik Rontala. This repository holds the download page and releases.
