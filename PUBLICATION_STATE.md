# Shared repository publication state

## 2026-10-12 Glamour Saver 1.0.0.1

- Release: https://github.com/Roxyz0501/GlamourSaver/releases/tag/v1.0.0.1
- ZIP: https://github.com/Roxyz0501/GlamourSaver/releases/download/v1.0.0.1/GlamourSaver-1.0.0.1.zip
- Source commit: `030dea3987406b9819366f627f5207709d822692`; SHA-256: `BBA007D82923D74D2D9AE85D645FAD000B8E2537B34E80A0397A321ED286C359`.
- Uses the exact canonical shared source and calls the trailing-tab helper once so Settings, Language settings, and Support remain the final tab group. Existing language choices, Config migration, Discord behavior, screenshot capture, and button positioning are preserved.
- Clean Release build completed with zero warnings/errors; localization, migration, canonical-source, tab-order, package-manifest, and secret checks passed. The public ZIP digest and packaged metadata were verified. Native in-game rendering, font coverage, and live Discord posting remain unverified.
- Shared index commit `55c5aca3d2bfbce68fa693f97d73b6801312a0de` updates only GlamourSaver to 1.0.0.1 and preserves all six other entries.

## 2026-10-12 Character Archive 1.0.0.1

- Release: https://github.com/Roxyz0501/CharacterArchive/releases/tag/v1.0.0.1
- ZIP: https://github.com/Roxyz0501/CharacterArchive/releases/download/v1.0.0.1/CharacterArchive-1.0.0.1.zip
- Source commit: `67a1fabc87c9ea12d9676833f94413957acfb0d2`; SHA-256: `518C2810904FF248EF5FFF63E4E34EB2B28DA25EF6F9E4DCB806C59E0A0FC13C`.
- Adopted the canonical trailing-tab helper. Overview, Details, and File Mapping are followed by Settings, Language settings, then Support; existing character archive, Lodestone lookup, job, playtime, and CSV behavior are preserved.
- Clean Release build completed with zero warnings/errors and all core checks passed, including the new tab-order regression checks. Public repository, PNG icon, ZIP hash, packaged manifest URLs/version and package contents were verified. Native in-game rendering remains unverified.
- Shared index entry commit `f07786d240274869788706e60d3825b3f09991ee` updates only CharacterArchive to 1.0.0.1 and preserves all six other entries.

## 2026-10-12 Aether Current Navigator 1.0.0.1

- Release: https://github.com/Roxyz0501/AetherCurrentUnlocker/releases/tag/v1.0.0.1
- ZIP: https://github.com/Roxyz0501/AetherCurrentUnlocker/releases/download/v1.0.0.1/AetherCurrentUnlocker-1.0.0.1.zip
- Source commit: `533ba2c`; SHA-256: `1D3BF0B531FA6121DA262332C1718C831443B34FAED87554A1687C145F4E39EB`.
- Uses the canonical trailing-tab helper so every plugin-specific tab is followed by Settings, Language settings, then Support. Clean Release build completed with zero warnings/errors; 134 static and 40 formatted localization keys passed. Native in-game rendering remains unverified.
- GitHub integration verified the uploaded Release asset digest and shared index commit `f283a308a240fbaa377720551245d12c57280867`; seven entries are preserved and AetherCurrentUnlocker is 1.0.0.1.

## 2026-10-12 Bait Beacon 1.0.0.1

- Release: https://github.com/Roxyz0501/BaitBeacon/releases/tag/v1.0.0.1
- ZIP: https://github.com/Roxyz0501/BaitBeacon/releases/download/v1.0.0.1/BaitBeacon-1.0.0.1.zip
- Source commit: `438cf1c8db04e52a8ee4db8731302d6665d77940`; SHA-256: `53CA72AA5E0B1C60A9479C2275308C094B70BDC06A0E37B9F47087E4423F462D`.
- Adopted the latest byte-identical canonical StandardPluginTabs.cs and its single trailing-tab helper. Lists is followed by Settings, Language settings, then Support. Saved lists, mooch bait, seven languages, and persistent highlight controls are preserved.
- Clean Release build: zero warnings/errors; 25 checks passed, including tab order. Public repository, PNG icon and ZIP returned HTTP 200; downloaded ZIP hash and packaged manifest author/version/RepoUrl/IconUrl/license/NOTICE verified. Native in-game tab, font and overlay rendering remain unverified.
- Shared index registration `bfd8b508a869681739bd466f14a29553b30339c6` changed only BaitBeacon and preserved six other entries. The anonymous commit-pinned URL returned HTTP 200 with seven entries and BaitBeacon 1.0.0.1. Normal `main` URL cache refresh is pending.

## 2026-10-11 BGMPlayer 1.0.0.0

- Release: https://github.com/Roxyz0501/AetherRadio/releases/tag/v1.0.0.0
- ZIP: https://github.com/Roxyz0501/AetherRadio/releases/download/v1.0.0.0/AetherRadio-1.0.0.0.zip
- Source commit: `6148f21ce6d476dd3a2b2e90e9a3e64eb80b3b1c`; SHA-256: `DCF7C7C75C8418B0A8E7014F6458511444F1939E3BD45BEAA0CCE52287039A42`.
- Added the independent localized Language settings tab and exact canonical language/Support implementation while preserving BGMPlayer's surrounding UI, saved language, lists and playback settings. Seven complete language dictionaries are embedded.
- Clean Release build: zero warnings/errors. 188 managed/offline checks and 45 isolated ImGui checks passed. Tab navigation and language changes made zero additional catalogue reads; unchanged views caused zero saves.
- Anonymous repository/icon/download URLs returned HTTP 200. Public ZIP hash, manifest identity/version/URLs, original icon and license notices verified. Native game font-atlas, IME/DPI and audio acceptance remain unverified; the Release remains a public preview.
- Only the AetherRadio entry is updated from 0.1.7.0 to 1.0.0.0; all six other entries are preserved.
- Registration commit: `71d9d7e991fd84bce941aa042c3acce16c5d71a5`. The anonymous commit-pinned and normal `main` URLs returned HTTP 200 with all seven entries and BGMPlayer 1.0.0.0 after revalidating the initially cached normal URL.

## 2026-10-11 Bait Beacon 1.0.0.0

- Release: https://github.com/Roxyz0501/BaitBeacon/releases/tag/v1.0.0.0
- ZIP: https://github.com/Roxyz0501/BaitBeacon/releases/download/v1.0.0.0/BaitBeacon-1.0.0.0.zip
- Source commit: `530322b0a40858d330473d664508ab41d0bb3df2`; SHA-256: `CD56C74BBAAB696C56909FA3D3301934BCE933874D9D00072E5FA15A8C293C79`.
- Copied the canonical StandardPluginTabs.cs exactly, moved the selector to an independent localized Language settings tab, standardized Support content and colors, and localized command help. Existing saved language, list and highlighting settings are retained.
- Clean Release build with zero warnings/errors and 23 checks. Public repository, PNG icon and ZIP returned HTTP 200; downloaded ZIP hash and packaged author/version/RepoUrl/IconUrl/license/NOTICE verified. Native tab rendering, font coverage and inventory overlay placement remain unverified.
- Shared index BaitBeacon entry updated to 1.0.0.0 in `0512713bb4aa8d34a778cfd1b6482f8a5d779133` while preserving all six other plugin entries. The anonymous commit-pinned and normal `main` URLs both returned HTTP 200 with seven entries and BaitBeacon 1.0.0.0 after the normal URL's cache refreshed.

## 2026-10-11 Character Archive 1.0.0.0

- Release: https://github.com/Roxyz0501/CharacterArchive/releases/tag/v1.0.0.0
- ZIP: https://github.com/Roxyz0501/CharacterArchive/releases/download/v1.0.0.0/CharacterArchive-1.0.0.0.zip
- Source commit: `4e8fd12cf9aec514a4857ab6ed1409186bdb97db`; SHA-256: `C22A3EED447643711FC93EC50A4051398DF2E0E65588A8092A542047A6ACB029`.
- Dedicated localized `Language settings###LanguageSettings` tab and canonical `Support###Support` implementation; existing seven-language detection, migration, persistence, and plugin behavior are preserved.
- Clean Release build completed with zero warnings/errors and all core checks passed. Public ZIP and packaged manifest were verified; in-game rendering remains unverified.

## 2026-10-11 Aether Current Navigator 1.0.0.0

- Release: https://github.com/Roxyz0501/AetherCurrentUnlocker/releases/tag/v1.0.0.0
- ZIP: https://github.com/Roxyz0501/AetherCurrentUnlocker/releases/download/v1.0.0.0/AetherCurrentUnlocker-1.0.0.0.zip
- Source commit: `e51af902099c00ba901f2bd4d6c7f6fc661ac17d`; SHA-256: `CB3D8C367807237E8089F46D853216ED87ABE7D5041452C0D66F4157D7A851E8`.
- Dedicated seven-language settings tab and standardized Roxyz0501 Support tab. Clean Release build completed with zero warnings/errors; localization checks covered 134 static strings and 40 formatted keys. Public ZIP and packaged manifest were verified; in-game rendering remains unverified.
- Shared entry update `10489d9` was verified anonymously at the commit-pinned and normal `main` URLs: HTTP 200, seven entries, AetherCurrentUnlocker 1.0.0.0.

## 2026-10-11 Bait Beacon 0.1.0.1

- Release: https://github.com/Roxyz0501/BaitBeacon/releases/tag/v0.1.0.1
- ZIP: https://github.com/Roxyz0501/BaitBeacon/releases/download/v0.1.0.1/BaitBeacon-0.1.0.1.zip
- Source commit: `b148885102ff72e64321efefbf86493305ae8986`; SHA-256: `2F9333D18DC3A60DCD4A97914771E6F2A228868828B35B7AE562072C1BF90B5B`.
- Rebuilt fish-bait snapshot from all 36 GatherBuddy Reborn patch files (2,616 fish recipes); fixed explicit and inherited mooch bait, skipped baitless spearfishing items, and reported only selected rod fish with no resolvable bait route.
- Added persistent overall highlighting toggle on list and Settings tabs. Expanded font glyph input for seven native language names and replaced the bait-list separator with ASCII.
- Clean Release build: zero warnings/errors; 19 checks passed. Public ZIP downloaded anonymously with matching SHA-256 and packaged manifest identity, RepoUrl, IconUrl, license and NOTICE verified. Updated native font rendering and overlay placement remain unverified.
- Shared repository entry updated from 0.1.0.0 to 0.1.0.1 in `65af7c89577f2e4d9d967cbb393cf004677e8bf3`; six other entries preserved. The anonymous commit-pinned and normal `main` URLs both returned HTTP 200 with seven entries and BaitBeacon 0.1.0.1 after the normal URL's cache refreshed.

## 2026-10-11 Bait Beacon 0.1.0.0

- New standalone public preview by Roxyz0501: https://github.com/Roxyz0501/BaitBeacon
- Release: https://github.com/Roxyz0501/BaitBeacon/releases/tag/v0.1.0.0
- ZIP: https://github.com/Roxyz0501/BaitBeacon/releases/download/v0.1.0.0/BaitBeacon-0.1.0.0.zip
- Source commit: `6cd37123432fdc4c1f6a62b0e4f28740e09a20fe`; SHA-256: `833E640A19DC31419DED660091D7AC74DB0DF724C69421894235BB1DF2F12599`.
- Dedicated public source and original PNG icon returned HTTP 200; downloaded Release ZIP matched the local hash and retained RepoUrl, IconUrl, author, version, license and NOTICE.
- Clean Release build with zero warnings/errors and 13 saved-list, bait, and localization checks passed. In-game overlay placement and font coverage remain unverified and are disclosed as preview limits.
- Shared repository index registration `95fd644cb9f2a6961cc96d0a059a23e9798a3455` adds BaitBeacon while preserving its six existing entries. The anonymous commit-pinned and normal `main` URLs both returned HTTP 200 with seven entries; the normal URL briefly returned its cached six-entry response (`max-age=300`) before refreshing.

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


## 2026-10-11 Allagan Local 0.2.0.2

- Release: https://github.com/Roxyz0501/AllaganLocal/releases/tag/v0.2.0.2
- ZIP: https://github.com/Roxyz0501/AllaganLocal/releases/download/v0.2.0.2/AllaganLocalPlugin-0.2.0.2.zip
- Source 3b54367; SHA-256 `771AF4E1C8CE6CF7DEEC50088190863D01B0C54777BD5D052B8270BA47C57C5C`.
- Keeps server alive across plugin/game exit, reuses existing instance, writes logs independently of parent pipes. Fixes exclusive sidebar selection and stale history responses.
- 13 host checks including actual parent process exit/reuse, 43 Web checks, clean Release zero warnings/errors and packaged runner validation passed. Native in-game acceptance unverified.
- Public repository/icon HTTP 200 (image/png) and downloaded ZIP hash verified. Five other entries unchanged.

- Shared registration `89bda8d2eb1a77433f3100e5f5c0abda1601224a` verified at both commit-pinned and normal main URLs: HTTP 200, six entries, Allagan Local 0.2.0.2.


## 2026-10-11 Allagan Local 1.0.0.0

- Release: https://github.com/Roxyz0501/AllaganLocal/releases/tag/v1.0.0.0
- ZIP: https://github.com/Roxyz0501/AllaganLocal/releases/download/v1.0.0.0/AllaganLocalPlugin-1.0.0.0.zip
- Source `976f6d492286cdf882bc236c4a68a442479d0f1b`; SHA-256 `0C3D7A7975181825B085230AD22BF5119571F09296297BB3198A95E8EB6E5B34`.
- Canonical StandardPluginTabs.cs copied byte-for-byte; separate LanguageSettings and Support tabs. Saved language, migration, browser sync and persistent server preserved. No new data/API requests.
- 485 localization, 44 font, 43 Web and 13 host checks passed. 1,361 codepoints covered by four fonts. Release zero warnings/errors; package startup/manifest verified. Native in-game acceptance unverified.
- Public repository/icon HTTP 200 (image/png), downloaded ZIP hash verified. Only Allagan Local index entry changed; all other entries preserved.

- Registration `cd0374b415897d0137aa26f735208506e543a1f6` verified anonymously at the pinned URL: HTTP 200, seven entries. Normal main URL retained cached 0.2.0.2 at verification. Unrelated BaitBeacon Tags whitespace restored; values were unchanged.

## 2026-10-11 Retainer Listing Helper 1.0.0.0

- Release: https://github.com/Roxyz0501/RetainerRecall/releases/tag/v1.0.0.0
- ZIP: https://github.com/Roxyz0501/RetainerRecall/releases/download/v1.0.0.0/RetainerRecall-1.0.0.0.zip
- Source commit: `179a70665fb70ef5bb71aa030f054defe511ac4e`; SHA-256: `50F9BB88BC196E102E9B6523161881026C14FCB21CC1196A623E92C5CB29F0D2`.
- Exact canonical Language settings and Support tab code; seven languages, existing choices and operation settings preserved. SDK-compatible read-only AgentRetainer layout adapted from official MIT source; native UI dispatch and validation retained.
- Clean Release build (zero warnings/errors), 149 managed checks, 16 native checks and 23 font/UI checks passed. Anonymous source/icon HTTP 200 (image/png) and public ZIP hash, manifest and seven resources verified. In-game rendering/operation and full-armoury retrieval remain unverified.
- Only the RetainerRecall index entry changed; all six other entries retained from latest main.


## 2026-10-12 Retainer Listing Helper 1.0.0.1

- Release: https://github.com/Roxyz0501/RetainerRecall/releases/tag/v1.0.0.1
- ZIP: https://github.com/Roxyz0501/RetainerRecall/releases/download/v1.0.0.1/RetainerRecall-1.0.0.1.zip
- Source: `5311e378b7fe332f0c10043921b349c85422b74c`; SHA-256: `A744D1D24D7353E906A542A4EECBE1573B415656F939D5C30B3A559FD0FA0E77`.
- Exact latest shared helper fixes the order: Listing, Recall, Settings, Language settings, Support. Editing controls moved to Settings; saved configuration and native behavior retained. Existing 1.0.0.0 assets untouched.
- Clean Release build (zero warnings/errors), 149 managed, 16 native and 25 order/font/UI checks passed. Anonymous repository/icon HTTP 200 (image/png); public ZIP hash, manifest and embedded languages verified. In-game rendering/operation and full-armoury retrieval remain unverified.
- Shared index commit `523a2dd00cfb292cd7e2f97ee165025b5ead86ec` was published through the GitHub connector after incorporating concurrent updates. Only RetainerRecall changed; six other entries preserved. Connector reads of pinned and main index URLs confirm seven entries, version 1.0.0.1 and correct ZIP.


## 2026-10-12 Allagan Local 1.0.0.1

- Release: https://github.com/Roxyz0501/AllaganLocal/releases/tag/v1.0.0.1
- ZIP: https://github.com/Roxyz0501/AllaganLocal/releases/download/v1.0.0.1/AllaganLocalPlugin-1.0.0.1.zip
- Source 85d9aee; shared registration `1b04fe414fd37cebfe0956ce4e95860917295fa6`.
- SHA-256: `23FB31B1EFBC1245A78F4B1FAF00FF2147E2BE25CB7ED46D086DAA3B1242C387`.
- Canonical trailing tab helper and order integration test passed; 485 localization checks and Release build zero warnings/errors. Package startup/manifest/resources verified. Native in-game rendering remains unverified. Existing 1.0.0.0 asset unchanged.
- Public repo/icon HTTP 200 (image/png), downloaded ZIP hash verified. Connector and pinned public index show 1.0.0.1; normal main raw URL retained cached 1.0.0.0. All other index entries preserved.
