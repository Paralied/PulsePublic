# Pulse

[Download Pulse for Windows](https://github.com/Paralied/PulsePublic/releases/latest/download/Pulse.exe) · [Release notes](https://github.com/Paralied/PulsePublic/releases)

A Windows x64 Roblox companion with saved game profiles, game-name search, public server browsing, a searchable friends list with Join, cursor presets, appearance options, client detection and update checks.

Put Pulse.exe in a writable folder. Pulse checks for newer releases automatically and asks before downloading and restarting. Downloads are verified against GitHub's SHA-256 asset digest. The previous executable is retained as `.previous`.

Enter your Roblox username once in **Friends**, select a friend and click **Join**. The signed-in Roblox client checks whether you can join; public status may be hidden.

## Release publishing

Development source is private. This repository contains compiled release packages and notes. Publishing a verified package under `dist/` triggers the public workflow, which creates a release with `Pulse.exe` and its checksum. It uses this repository's built-in GitHub Actions token; no personal token or user setup is required.

Cursor/sound changes depend on Roblox's client asset layout. FPS unlocking remains unfinished.
