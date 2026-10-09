# MultiDock

[Svenska](README.md) | **English**

A dock for every display on macOS. This is where the ready-made versions of MultiDock are available for download.

## Install

1. Download the latest `MultiDock-<version>.dmg` under [Releases](https://github.com/SpeedSurfer491/MultiDock-releases/releases/latest).
2. Open the DMG file and drag MultiDock to the Applications folder.
3. Open MultiDock from the Applications folder.

MultiDock is free and not notarized by Apple, so the first time, macOS says the app can't be checked for malicious software. That only means Apple hasn't reviewed it. Do this once:

1. Click **Done** in the warning, not "Move to Trash".
2. Open **System Settings → Privacy & Security** and scroll down to the **Security** section.
3. Click **Open Anyway** next to MultiDock and confirm with your password or Touch ID.
4. Click **Open** in the dialog that appears.

If you prefer Terminal, you can remove the download flag instead, so the warning never appears:

```bash
xattr -dr com.apple.quarantine /Applications/MultiDock.app
```

MultiDock then asks for the **Accessibility** permission (to move and keep track of windows) and, if you turn on images in the previews, for **Screen Recording**.

## Now Playing

A tile in the dock shows and controls what's playing in **Music Assistant**, **TIDAL** or **Spotify**: artwork, song, play/pause, next, previous, scrubbing and volume (TIDAL has no artwork or progress). In Settings → General you choose which source is shown when several are playing or none is, and you can switch source whenever you like by right-clicking the tile → "Source" or with the icons in the panel.

For Spotify, macOS asks the first time whether MultiDock may **control Spotify**. Without it the song is still shown, but without artwork and volume, and the buttons don't work. Change the choice in System Settings → Privacy & Security → Automation. Music Assistant needs the server's address and a token, entered in Settings → General.

## Updates

MultiDock updates itself. It checks for a new version here once a day and asks whether to install it, and you can also choose "Check for Updates…" in the menu bar menu. The updates are signed, and an automatic update doesn't need to be approved with Open Anyway.

If you have version 1.0.18 or older, install the latest version manually once, following the instructions above.

## Source code

MultiDock's source code is not public. The "Source code (zip)" and "Source code (tar.gz)" archives under each version are created automatically by GitHub and contain only these README files. The `.dmg` file is the one to download.

## Support MultiDock

MultiDock is free. If you'd like to buy me a coffee, you can do so on [Ko-fi](https://ko-fi.com/jesperkinnas). The link is also in the app under Settings → About.

## License

MultiDock is free to download and use on your own computers, but may not be sold or redistributed, modified or unmodified; link here instead. The app is provided as is, without warranty. The full license, and the license for [Sparkle](https://sparkle-project.org), which handles updates, are in the app under Settings → About → License and Third-Party Code.

Requires macOS 27.
