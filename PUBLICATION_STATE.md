# Shared repository publication state

## 2026-10-08 Retainer Listing Helper 0.2.0.0

- Updated existing RetainerRecall entry to display name Retainer Listing Helper. Source/internal identity retained.
- Release: https://github.com/Roxyz0501/RetainerRecall/releases/tag/v0.2.0.0
- ZIP: https://github.com/Roxyz0501/RetainerRecall/releases/download/v0.2.0.0/RetainerRecall-0.2.0.0.zip
- Added session-only NQ/HQ-shared price memory, configurable shortcut/delay and Marketbuddy quantity-setting reads; listing and recall both use ordinary UI menus. Direct market movement calls removed.
- Clean Release build, 81 managed checks and isolated configuration UI/command/persistence checks passed. In-game behavior and packet equivalence remain unverified and disclosed.
- Anonymous source/icon HTTP 200, PNG content type and public ZIP hash verified; packaged identity, notices and absence of direct market movement calls checked.
- SHA-256: `98E28252C72E2E43F6852C5B7FD5338E129CBB1FB41026D36431D14644D740FA`.
- Other four plugin entries preserved. Remote shared-index verification pending.

## 2026-10-08 Retainer Recall initial publication

- Added Retainer Recall 0.1.0.0, author Roxyz0501; new standalone plugin.
- Source: https://github.com/Roxyz0501/RetainerRecall
- Release: https://github.com/Roxyz0501/RetainerRecall/releases/tag/v0.1.0.0
- ZIP: https://github.com/Roxyz0501/RetainerRecall/releases/download/v0.1.0.0/RetainerRecall-0.1.0.0.zip
- Icon: https://raw.githubusercontent.com/Roxyz0501/RetainerRecall/main/images/icon.png
- Repository/icon returned anonymous HTTP 200; icon content type image/png. Public ZIP downloaded and matched local SHA-256 `9A1C65AF1FB8D6AE79A44C3AE24540E51F7AB455F8E0C958A9A218C32C702511`.
- Packaged author, RepoUrl, IconUrl and notices checked; original 512x512 icon included. No other plugin dependencies; Dalamud API 15/.NET 10/x64.
- Clean Release build: zero warnings/errors; 27 managed checks passed. In-game native retrieval/UI placement remain unverified and disclosed.
- Existing four plugin entries preserved. Anonymous main and commit-pinned index verified as 0.1.0.0 in registration commit `287dc436531e03fe5751d96091b5f78ef356d175`.

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
