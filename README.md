# scoop-lyrenne

A [Scoop](https://scoop.sh) bucket for **[Lyrenne](https://github.com/Doctordefector/Lyrenne)**, a free, open source YouTube Music player for Windows 10 and 11.

## Install

```powershell
scoop bucket add lyrenne https://github.com/Doctordefector/scoop-lyrenne
scoop install lyrenne
```

## Update

```powershell
scoop update lyrenne
```

Your library, login and downloads live in Scoop's persisted `data` and `Downloads` folders, so updating never signs you out.

> Update through Scoop rather than the in-app updater in Settings. The in-app one writes over the Scoop install directory. It is manual-only, so it never fires on its own.

## Uninstall

```powershell
scoop uninstall lyrenne
```

Add `--purge` to also delete the persisted library and downloads.

## What is Lyrenne?

A native Compose Desktop (JVM) YouTube Music player, not a browser wrapper. It signs in to your own account, syncs your real library both ways, and bundles the VLC playback engine, ffmpeg and its own Java runtime. Synced lyrics, a 10-band equalizer, crossfade, downloads, Discord Rich Presence, Last.fm scrobbling and Listen Together rooms.

Full details: **[Doctordefector/Lyrenne](https://github.com/Doctordefector/Lyrenne)** · [Website](https://doctordefector.github.io/Lyrenne/)

## Notes

Lyrenne was called Metrolist Desktop until 2.9.2. The manifest still points at the `Metrolist-2.9.2-portable.zip` asset because that is what the current release ships; the `autoupdate` block switches the URL, `extract_dir` and shortcut over to the Lyrenne names automatically on the next release.

Manifests here are kept current by [Excavator](https://github.com/ScoopInstaller/GithubActions), which runs daily.

The official [Scoop Extras](https://github.com/ScoopInstaller/Extras) bucket requires 100+ stars or 50+ forks, so this bucket provides the install path until Lyrenne clears that bar.
