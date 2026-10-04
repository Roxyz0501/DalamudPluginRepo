# Shared repository publication state

Updated: 2026-10-04 (JST).

- Shared index: https://raw.githubusercontent.com/Roxyz0501/DalamudPluginRepo/main/repo.json
- Updated BGMPlayer to 0.1.5.0: temporarily suppresses the local Orchestrion music bus during playback, restoring it on stop/logout/unload. No furniture commands or packet sends.
- Dedicated source: https://github.com/Roxyz0501/AetherRadio
- Release: https://github.com/Roxyz0501/AetherRadio/releases/tag/v0.1.5.0
- ZIP: https://github.com/Roxyz0501/AetherRadio/releases/download/v0.1.5.0/AetherRadio-0.1.5.0.zip
- Icon: https://raw.githubusercontent.com/Roxyz0501/AetherRadio/main/images/icon.png
- Verified unauthenticated HTTP 200 for repository, PNG icon and ZIP before registration.
- Downloaded ZIP SHA-256: `928D376B8C2015D7D719D7156AD11EE6CFC5B217F6DB80FD51AD8B1D4121DF3B`.
- Packaged RepoUrl/IconUrl, author and MIT third-party notice verified.
- Required plugin dependencies: none. Dalamud API 15, x64, .NET 10.
- Clean Release build, 55 managed checks and 64 including offline game data passed. UI unchanged. Native in-game orchestrion switching and audio restoration remain unverified.
- Existing Glamour Saver, Character Archive and Aether Current Navigator entries were preserved.

- InternalName remains AetherRadio to retain the existing update/config identity. No duplicate BGMPlayer index entry.
- User declined seek support. No alternate playback engine was added.
