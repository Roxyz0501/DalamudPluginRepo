# Shared repository publication state

## 2026-10-08 Allagan Local 0.2.0.0

- Registration `1e165529bccec42614860284ef74397f6ce9655f` verified anonymously at commit-pinned and normal main URLs: HTTP 200, six entries, Allagan Local 0.2.0.0.

- Release: https://github.com/Roxyz0501/AllaganLocal/releases/tag/v0.2.0.0
- ZIP: https://github.com/Roxyz0501/AllaganLocal/releases/download/v0.2.0.0/AllaganLocalPlugin-0.2.0.0.zip
- Source: `450260521c130dc75730732a27057c39a49ab173`. SHA-256: `80EACB814A60EFFC8FDC33D3125E28EC9DFC10B2A2DCC32FB0E6553F5D810C1F`.
- Seven-language localization, persisted language policy, live website synchronization and licensed CJK subsets.
- Clean Release: zero warnings/errors; 410 localization checks, 42 web tests, nine lifecycle checks and isolated package checks passed. Native in-game acceptance remains unverified.
- Anonymous public repository/icon HTTP 200 (image/png), downloaded ZIP hash and manifest URLs/author/version verified. All five other plugin entries preserved, including Character Archive 0.6.0.0 and Retainer Listing Helper 0.3.0.0.


## 2026-10-08 seven-language releases

- Character Archive 0.6.0.0: https://github.com/Roxyz0501/CharacterArchive/releases/tag/v0.6.0.0
- ZIP: https://github.com/Roxyz0501/CharacterArchive/releases/download/v0.6.0.0/CharacterArchive-0.6.0.0.zip
- Source commit: `afa953c58cfdbb5ac33b21d3bbf0680fa13eb889`; SHA-256: `642FE0054C613AB38F62AF3B85F0356675FA4313C30934D7A331342105CA1FC0`.
- Retainer Listing Helper 0.3.0.0: https://github.com/Roxyz0501/RetainerRecall/releases/tag/v0.3.0.0
- ZIP: https://github.com/Roxyz0501/RetainerRecall/releases/download/v0.3.0.0/RetainerRecall-0.3.0.0.zip
- Source commit: `fcb166c367148e53e55c69ddd7dac3842b1c9ee0`; SHA-256: `D515D0DAC1C3B4835DA699E43EA266620D43210B85C1359E7CE72F7F003A634B`.
- Both releases add ja/en/de/fr/ko/zh-Hans/zh-Hant selection, one-time game/Dalamud language detection and persisted manual choices. Character Archive CSV headers remain fixed for interoperability.
- Clean Release builds passed with zero warnings/errors. Character Archive core/localization/CSV tests passed; Retainer Listing Helper passed 149 managed, 12 native boundary and 20 font/UI checks.
- Dedicated source/icon URLs returned anonymous HTTP 200 (icons image/png); public ZIP hashes and packaged manifest metadata verified by each publishing task. In-game acceptance remains unverified; Retainer Listing Helper's full-armoury retrieval stop remains unresolved and disclosed.
- Shared index registration `f77e9c064eeb932758fc3682c32ebf4f59e64a0a` verified anonymously with HTTP 200 at both the commit-pinned and normal main URLs. Both contain all six entries, the two new versions, and four unchanged plugin entries.

## 2026-10-08 Allagan Local 0.1.0.1

- Release: https://github.com/Roxyz0501/AllaganLocal/releases/tag/v0.1.0.1
- ZIP: https://github.com/Roxyz0501/AllaganLocal/releases/download/v0.1.0.1/AllaganLocalPlugin-0.1.0.1.zip
- SHA-256: `5ACEE10D54FFB8B202BA09A5C6504AF2BA03ED438A660E82708A0616ED220FE0`.
- Startup remains enabled by default. Restart replaces only the owned server and also starts a stopped server. External processes remain untouched.
- Optional local browser-settings migration seed restores missing preferences; no private seed/data is distributed.
- Clean build, nine lifecycle checks, packaged startup and migration-preservation/cross-origin checks passed. Public ZIP hash/manifest verified. Native restart button has not been exercised in game.

## 2026-10-08 Retainer Listing Helper 0.2.0.3

- Removed floating status/settings window. Settings remain available from the plugin installer and commands. No execution changes.
- Release: https://github.com/Roxyz0501/RetainerRecall/releases/tag/v0.2.0.3
- ZIP: https://github.com/Roxyz0501/RetainerRecall/releases/download/v0.2.0.3/RetainerRecall-0.2.0.3.zip
- Source commit `341c6ee`; SHA-256 `67D4CAFCDC133732BF42D2A997B7F96C779A672B5CFDA2DD282B75A7F00C1C8E`.
- Clean Release build and five existing UI harness checks passed. Public source/icon HTTP 200, image/png and ZIP hash/manifest verified. Five other entries preserved. Shared registration `d5d7d29a19961b54ddd578860fb14fcc076f6f21` verified at the anonymous commit-pinned URL with six entries. Normal main URL still returned cached 0.2.0.2 at verification, including after no-cache revalidation; installer visibility may be delayed by CDN caching.

## 2026-10-08 Retainer Listing Helper 0.2.0.2 crash fix

- Release: https://github.com/Roxyz0501/RetainerRecall/releases/tag/v0.2.0.2
- ZIP: https://github.com/Roxyz0501/RetainerRecall/releases/download/v0.2.0.2/RetainerRecall-0.2.0.2.zip
- Source release commit: `7706ea0`; SHA-256: `2888F4FE1E0F20EF2E8E9FF8C2AC95D428D90C4BA98384E98F34E1CC8229144B`.
- Fixes native listing confirmation crash caused by omitted AtkEventData. Registered click now receives initialized input; owner null check occurs before IsEnabled.
- Clean Release build, 90 managed checks, 12 native ABI checks passed. Previous omitted argument fails the regression test. Corrected in-game operation remains unverified.
- Anonymous repository/icon HTTP 200, image/png, downloaded ZIP metadata and hash verified. No raw crash data included. Shared index registration `38c2f77f30d0165dd36f56833ed17f5d57884b5b` verified anonymously at both pinned and normal main URLs; six entries with all five others preserved.

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


## 2026-10-09 Allagan Local 0.2.0.1 crash fix

- Release: https://github.com/Roxyz0501/AllaganLocal/releases/tag/v0.2.0.1
- ZIP: https://github.com/Roxyz0501/AllaganLocal/releases/download/v0.2.0.1/AllaganLocalPlugin-0.2.0.1.zip
- Source: 33a5983. SHA-256: `3537016F371A047E54DE79E3A42F90F5DA69C68F5BA2A2C21F607E0B9BAC81A3`.
- Font additions gated by actual PreBuild phase. 44 real-SDK regression checks, 410 localization checks and packaged verification passed; Release zero warnings/errors. Native in-game startup remains unverified.
- Public repository/icon HTTP 200 (image/png), ZIP hash verified. Five other index entries unchanged.


## 2026-10-09 Allagan Local 0.2.0.1 — published

- User explicitly authorized publication. Release: https://github.com/Roxyz0501/AllaganLocal/releases/tag/v0.2.0.1
- ZIP: https://github.com/Roxyz0501/AllaganLocal/releases/download/v0.2.0.1/AllaganLocalPlugin-0.2.0.1.zip
- Source 33a5983; shared registration ee5098524dc99e270bb44b0ee17e0356f8c5d755.
- SHA-256: `3537016F371A047E54DE79E3A42F90F5DA69C68F5BA2A2C21F607E0B9BAC81A3`. Anonymous ZIP hash and repository/icon HTTP 200 verified. Shared commit-pinned URL verified: six entries, five other entries unchanged. Normal main URL still returned cached 0.2.0.0 at verification; installer visibility may be delayed by CDN caching.
- 44 font lifecycle checks, 410 localization checks, Release build zero warnings/errors and package checks passed. Native in-game startup remains unverified. Installed DLL was not replaced.
