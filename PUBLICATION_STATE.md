# Shared repository publication state

## 2026-10-08 Retainer Listing Helper 0.2.0.2 crash fix

- Release: https://github.com/Roxyz0501/RetainerRecall/releases/tag/v0.2.0.2
- ZIP: https://github.com/Roxyz0501/RetainerRecall/releases/download/v0.2.0.2/RetainerRecall-0.2.0.2.zip
- Source release commit: `7706ea0`; SHA-256: `2888F4FE1E0F20EF2E8E9FF8C2AC95D428D90C4BA98384E98F34E1CC8229144B`.
- Fixes native listing confirmation crash caused by omitted AtkEventData. Registered click now receives initialized input; owner null check occurs before IsEnabled.
- Clean Release build, 90 managed checks, 12 native ABI checks passed. Previous omitted argument fails the regression test. Corrected in-game operation remains unverified.
- Anonymous repository/icon HTTP 200, image/png, downloaded ZIP metadata and hash verified. No raw crash data included. Five other plugin entries preserved; shared index verification pending.

## 2026-10-08 Retainer Listing Helper 0.2.0.1

- Release: https://github.com/Roxyz0501/RetainerRecall/releases/tag/v0.2.0.1
- ZIP: https://github.com/Roxyz0501/RetainerRecall/releases/download/v0.2.0.1/RetainerRecall-0.2.0.1.zip
- SHA-256: `7A43B67D03354E02882B22EE527A62F5D397A5FB9CA695AFDB23058469C9273B`.
- Dedicated source release commit `8c70bb1`. Anonymous source/icon HTTP 200, image/png and downloaded public ZIP hash verified; packaged metadata and notices retained.
- 0.1-second minimum listing/recall delay; armoury equipment included in player listing scans and recall acknowledgement; inventory shortcut observed after the original menu-opening function; chat diagnostics added.
- Clean Release build, 90 managed checks and five isolated UI/command/persistence checks passed. In-game shortcut/armoury behavior and resolution of the reported full-armoury stop remain unverified.
- Anonymous commit-pinned and normal main shared index verified at registration commit `98d10e097dcd96852f744340d9d9afbef1172f9d`; six entries, with all five other plugins preserved.

## 2026-10-08 Allagan Local 0.1.0.0

- Initial public preview, new standalone plugin, author Roxyz0501.
- Source: https://github.com/Roxyz0501/AllaganLocal
- Release: https://github.com/Roxyz0501/AllaganLocal/releases/tag/v0.1.0.0
- ZIP: https://github.com/Roxyz0501/AllaganLocal/releases/download/v0.1.0.0/AllaganLocalPlugin-0.1.0.0.zip
- SHA-256: `CAC3985CD433F1A8DADCAC90DFCB8AD6046BF95862481438C58BB256C4D6EBCF`.
- Source/icon anonymous HTTP 200 and image/png verified. Downloaded ZIP identity, notices and absence of personal data checked.
- Requires Allagan Tools saved inventory/gil; AllaganMarket additionally required for sales history. Sources are not bundled. Node.js runtime and complete license bundled.
- Clean Release build, 39 site tests, six host lifecycle checks, packaged startup and seven locale dictionaries verified. In-game acceptance and complete translations remain pending and disclosed.
- Five existing index entries preserved.
- Registration commit: `18bcc1658395cfd19a544dff033bf1f338f7203c`. Anonymous commit-pinned index verified with six entries. Normal main URL initially retained its cached five-entry response (max-age 300).

## 2026-10-08 Retainer Listing Helper 0.2.0.0

- Updated existing RetainerRecall entry to display name Retainer Listing Helper. Source/internal identity retained.
- Release: https://github.com/Roxyz0501/RetainerRecall/releases/tag/v0.2.0.0
- ZIP: https://github.com/Roxyz0501/RetainerRecall/releases/download/v0.2.0.0/RetainerRecall-0.2.0.0.zip
- Added session-only NQ/HQ-shared price memory, configurable shortcut/delay and Marketbuddy quantity-setting reads; listing and recall both use ordinary UI menus. Direct market movement calls removed.
- Clean Release build, 81 managed checks and isolated configuration UI/command/persistence checks passed. In-game behavior and packet equivalence remain unverified and disclosed.
- Anonymous source/icon HTTP 200, PNG content type and public ZIP hash verified; packaged identity, notices and absence of direct market movement calls checked.
- SHA-256: `98E28252C72E2E43F6852C5B7FD5338E129CBB1FB41026D36431D14644D740FA`.
- Other four plugin entries preserved. Anonymous commit-pinned shared index verified at `df395dcf0697c2069e7788aa3cc35b01a0f40dc4` with new display name/version and ZIP URLs. Normal main raw URL initially returned cached 0.1.0.0; revalidation and a subsequent ordinary request both returned 0.2.0.0.

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
