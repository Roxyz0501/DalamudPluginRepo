# Shared repository publication state

Updated: 2026-10-04 (JST).

- Shared index: https://raw.githubusercontent.com/Roxyz0501/DalamudPluginRepo/main/repo.json
- Updated BGMPlayer to 0.1.7.0: adds 0-200% volume, repeat buttons in both players and one-track repeat by default, including a one-time existing-config migration. Game audio settings and non-music buses are unchanged.
- Dedicated source: https://github.com/Roxyz0501/AetherRadio
- Release: https://github.com/Roxyz0501/AetherRadio/releases/tag/v0.1.7.0
- ZIP: https://github.com/Roxyz0501/AetherRadio/releases/download/v0.1.7.0/AetherRadio-0.1.7.0.zip
- Icon: https://raw.githubusercontent.com/Roxyz0501/AetherRadio/main/images/icon.png
- Verified unauthenticated HTTP 200 for repository, PNG icon and ZIP before registration.
- Downloaded ZIP SHA-256: `9FB0D2FCE535398FA1533D5011106CA7636F1F5FF969B93118B797CD33224AC5`.
- Packaged RepoUrl/IconUrl, author and MIT third-party notice verified.
- Required plugin dependencies: none. Dalamud API 15, x64, .NET 10.
- Clean Release build, 67 managed checks, 76 including offline game data, and the UI/command harness passed. Native in-game audio and loop acceptance remain unverified.
- Existing Glamour Saver, Character Archive and Aether Current Navigator entries were preserved.

- InternalName remains AetherRadio to retain the existing update/config identity. No duplicate BGMPlayer index entry.
- User declined seek support. No alternate playback engine was added.

- 0.1.6.0 remains a GitHub prerelease; the shared index skipped it when the user requested one-track repeat as default during publication.
