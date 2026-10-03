# Shared repository publication state

Updated: 2026-10-04 (JST).

- Shared index: https://raw.githubusercontent.com/Roxyz0501/DalamudPluginRepo/main/repo.json
- Updated BGMPlayer to 0.1.4.0: logout resets playback state and releases hooks; next manual play creates a fresh engine. Saved playlists and settings are preserved.
- Dedicated source: https://github.com/Roxyz0501/AetherRadio
- Release: https://github.com/Roxyz0501/AetherRadio/releases/tag/v0.1.4.0
- ZIP: https://github.com/Roxyz0501/AetherRadio/releases/download/v0.1.4.0/AetherRadio-0.1.4.0.zip
- Icon: https://raw.githubusercontent.com/Roxyz0501/AetherRadio/main/images/icon.png
- Verified unauthenticated HTTP 200 for repository, PNG icon and ZIP before registration.
- Downloaded ZIP SHA-256: `500B84C5838CFB0A1F6B51C976114AE4F7F8E2D0A8CBB18672E4DB8F71FE6F42`.
- Packaged RepoUrl/IconUrl, author and MIT third-party notice verified.
- Required plugin dependencies: none. Dalamud API 15, x64, .NET 10.
- Clean Release build, 44 managed checks, 53 including offline game data, and command/UI harness passed. Native in-game logout/relogin and audio restoration remain unverified.
- Existing Glamour Saver, Character Archive and Aether Current Navigator entries were preserved.

- InternalName remains AetherRadio to retain the existing update/config identity. No duplicate BGMPlayer index entry.
- User declined seek support. No alternate playback engine was added.
