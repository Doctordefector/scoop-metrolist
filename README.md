# scoop-metrolist

A [Scoop](https://scoop.sh) bucket for **[Metrolist Desktop](https://github.com/Doctordefector/Metrolist-Desktop)** — a free, open source YouTube Music client for Windows 10 and 11.

## Install

```powershell
scoop bucket add metrolist https://github.com/Doctordefector/scoop-metrolist
scoop install metrolist-desktop
```

## Update

```powershell
scoop update metrolist-desktop
```

Your library, login and downloads live in Scoop's persisted `data` and `Downloads` folders, so updating never signs you out.

> Update through Scoop rather than the in-app updater in Settings — the in-app one writes over the Scoop install directory. It is manual-only, so it never fires on its own.

## Uninstall

```powershell
scoop uninstall metrolist-desktop
```

Add `--purge` to also delete the persisted library and downloads.

## What is Metrolist Desktop?

A native Compose Desktop (JVM) YouTube Music client — not a browser wrapper. It signs in to your own account, syncs your real library both ways, and bundles the VLC playback engine, ffmpeg and its own Java runtime. Synced lyrics, 10-band equalizer, crossfade, downloads, Discord Rich Presence, Last.fm scrobbling, Listen Together rooms.

Full details: **[Doctordefector/Metrolist-Desktop](https://github.com/Doctordefector/Metrolist-Desktop)** · [Website](https://doctordefector.github.io/Metrolist-Desktop/)

Looking for the Android app? → [MetrolistGroup/Metrolist](https://github.com/MetrolistGroup/Metrolist)

## Why a separate bucket?

Scoop's `extras` bucket requires a project to have 100+ stars or 50+ forks. Metrolist Desktop is not there yet, so this bucket provides the install path in the meantime. Manifests here are kept current automatically by [Excavator](https://github.com/ScoopInstaller/GithubActions).
