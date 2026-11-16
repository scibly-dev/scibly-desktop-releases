# Scibly for Mac

> [!TIP]
> **[⬇ Get Scibly from the latest release](https://github.com/scibly-dev/scibly-desktop-releases/releases/latest)**: download **Scibly.dmg** under *Assets*.
> Older versions are under [all releases](https://github.com/scibly-dev/scibly-desktop-releases/releases).

Needs macOS 14.2 or later, on Apple silicon or Intel.

> [!IMPORTANT]
> **Run this command before you open the DMG.** Scibly is not notarized by Apple yet, so macOS blocks it with
> “Apple could not verify ‘Scibly.dmg’ is free of malware”. The command removes the download’s quarantine flag, and macOS then opens it without asking:
>
> ```sh
> xattr -dr com.apple.quarantine ~/Downloads/Scibly.dmg
> ```
>
> Saved the DMG somewhere else? Change the path. Only run this on a file you downloaded from these releases.

## Install

1. Download **Scibly.dmg** from the [latest release](https://github.com/scibly-dev/scibly-desktop-releases/releases/latest).
2. Run the command above in Terminal.
3. Open the DMG and drag Scibly into Applications.

Already saw the warning? Click **Done** (not “Move to Bin”), then open System Settings → Privacy & Security, scroll down and click **Open Anyway**. macOS may ask once more for the app itself: do the same again.

## Updates

Scibly updates itself: it checks for a new version at each start and installs it on the next one. You never need to download it again.
