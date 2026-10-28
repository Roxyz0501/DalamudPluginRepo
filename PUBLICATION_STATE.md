# Shared repository publication state

## 2026-10-28 — BGMPlayer 1.1.2.0 supplementary installed tracks

- Release: https://github.com/Roxyz0501/AetherRadio/releases/tag/v1.1.2.0
- ZIP: https://github.com/Roxyz0501/AetherRadio/releases/download/v1.1.2.0/AetherRadio-1.1.2.0.zip
- Source/tag: `a397996e32487214964990866394ef7d8b6391e2`; ZIP 1,390,861 bytes, 10 files; SHA-256 `EB6FA5EAB30218A17A6AFAACF53A62F611385C9D125C97D20B8CB3405FD45913`.
- Catalogue now reads installed music from OrchestrionPath as well as BGM, including untitled or content-unassigned rows, with stable supplementary IDs and path deduplication. 闘う者達 (row 857) and 更に闘う者達 (row 858) are available under Other; hiragana search is supported. No game audio is distributed.
- Supplementary playback uses scoped local SoundManager.PlayBGMSound path substitution under the existing BGM scene lifecycle. Plugin-only IDs never go to SetBGM; OrchestrionManager.PlayTrack (which may send server packets) and PlaySample are not called. Music-only volume and cleanup ownership retained.
- Clean Release zero warnings/errors; 248 managed / 269 offline-data checks and 92 isolated ImGui checks pass. Installed catalogue has 2,179 tracks including 886 supplementary; initial requests: 11 sheets and 2,181 file checks, subsequent navigation reads zero. Synthetic UI persistence: three commits / 1,348 logical payload bytes including initial fixture.
- Anonymous repository/icon/ZIP HTTP 200, icon image/png, downloaded ZIP and GitHub asset digest match; packaged version/author/URLs and license notices verified. Public prerelease, not draft.
- Shared index commit `350643c21de5cbf6806a0db708ca969fd22016c7`; anonymous main and pinned indexes both show 1.1.2.0 with 14 entries. All 13 other entries preserved.
- Published under standing project authorization. Connector used for source/index/ledgers, CLI only for unsupported Release/assets and local Git objects. No production settings or installed DLL replaced. Actual supplementary audio, SCD looping/bus behavior, carrier transitions, stop/logout/dispose restoration and live font-atlas/IME/DPI remain unverified; limitations are explicit in Release notes and VALIDATION.md. Unreferenced hashed archive entries are outside discovery scope.

## 2026-10-25 — Character Archive 1.1.0.0 MSQ progress and review fixes

- Release: https://github.com/Roxyz0501/CharacterArchive/releases/tag/v1.1.0.0
- ZIP: https://github.com/Roxyz0501/CharacterArchive/releases/download/v1.1.0.0/CharacterArchive-1.1.0.0.zip
- Source/tag: `05c7e16bc9ce5b2e6dfa4265cd4c9182debbd3eb`; ZIP 98,064 bytes, four allowlisted files; SHA-256 `E66F4C3E27B40F58D77F377B318F200847D1F74FE90D879A8C0E9F2103D4B1E9`.
- Added per-character read-only main-scenario progress in Overview and Details. Cached installed quest graph, selected guide path, accepted/last-completed state and verified endpoint completion; 10-second local reads, changed-only persistence, offline snapshots and no extra server requests.
- Reviewed all production code and fixed nine issue groups: exact Lodestone identity, face/HTTP failure handling and safe bounded requests, late manual-edit overwrite, login readiness/early playtime buffering, future/invalid configuration recovery, backup maintenance retry, UI caching/identity/scrolling, CSV durability and localization/privacy. See REVIEW_2026-10-25.md.
- Clean locked-dependency Release rebuild: zero warnings/errors. Existing core and all-UI seven-language keys plus 43 persistence, 57 MSQ/review and 12 offline catalogue checks passed. Installed catalogue: 1,050 MSQs in each of four game languages with matching endpoint. Synthetic 600 edits: one save / 238 logical bytes; unchanged periods and MSQ observations: zero extra writes/dirty marks. Physical SSD IO and native game behavior remain unverified.
- Anonymous repository/release/icon HTTP200 (image/png); public ZIP hash and manifest verified. Shared index `c5f82f938d7cb50af16fc976c1a7b163a9809a9c`: connector, pinned and normal main raw URLs verified at 1.1.0.0; all 13 other entries preserved.
- Published under the 2026-10-23 project-wide continuing authorization. Connector used for supported source/index/records; CLI for Release/assets and local Git synchronization. No installed DLL or production configuration replaced. Real game acquisition/lifecycle, live Lodestone markup and seven-language visual/font acceptance remain unverified.


## 2026-10-25 — Bait Beacon 1.0.0.3 review fixes

- Release: https://github.com/Roxyz0501/BaitBeacon/releases/tag/v1.0.0.3
- ZIP: https://github.com/Roxyz0501/BaitBeacon/releases/download/v1.0.0.3/BaitBeacon-1.0.0.3.zip
- Source/tag: `fc979cfc700df1c0177bc892e8012ca99d0abee3`; ZIP 67,463 bytes, five allowlisted files; SHA-256 `EF62E7DFD454982BB5AD32F41F6C8F34A80EFB9A821F0C6E96ACBFA3601E6A89`.
- Fixed incomplete target/prerequisite bait detection, malformed list snapshot replacement, retainer page 6/7 exclusion and glyph coverage for new list names. Quantity display now scans inventory once for all relevant bait.
- 81 offline checks passed; previous resolver/reader reproduce new regression failures; 2,616 recipes checked for cycles. Release zero warnings/errors; shared tabs match canonical source. See REVIEW_2026-10-25.md for evidence and limitations.
- Anonymous repository/icon HTTP200 (image/png), ZIP hash and packaged manifest verified. Shared index commit `19d60195b6b0680a225d139dbc83bc4f9fb03a07`: pinned and normal main URLs verified at 1.0.0.3; all 13 other entries preserved.
- Published under the project-wide continuing authorization dated 2026-10-23. Connector used for supported source/index/records; CLI for unsupported Release/assets and local Git sync. Live-game overlay/font-atlas/lifecycle remain unverified. No installed DLL or production configuration modified.


## 2026-10-25 — Gil Ledger 1.2.0.1 review fixes published

- Release: https://github.com/Roxyz0501/MarketLedger/releases/tag/v1.2.0.1
- ZIP: https://github.com/Roxyz0501/MarketLedger/releases/download/v1.2.0.1/MarketLedger-1.2.0.1.zip
- Source/tag: `ace6cc92a4c6f40f6a9e2e73d74eb87d401a3f3a`; ZIP 144,693 bytes, 11 allowlisted files; SHA-256 `0B70E3FC44D6054F82C51514A3482541A0DBF61F740224716864C1A07375EA06`.
- Fixed seven reproduced issue groups: shutdown CSV join after query faults; UI-context logout-flush deadlock; pending spending loss on automatic pause; CSV partial-file collision deletion; empty-export cancellation; invalid recovery IDs/timestamps/totals; Windows-calendar date filter mismatch.
- 4,252 checks passed: 872 core, 57 persistence, 3,312 native ImGui/glyph/lifecycle, 6 new core review and 5 new lifecycle/culture checks. Clean Release zero warnings/errors; canonical helpers match; source/DLL credential/local-path scans and package checks passed. See VALIDATION.md for reproductions and measured IO.
- Anonymous repository/icon HTTP200 (image/png), ZIP hash/manifest verified. Shared index `759bad7977f9899e0042b1e6f1e5dc1988e3db28`: commit-pinned and normal main URLs verified at 1.2.0.1; all 13 other entries preserved, including a concurrent new registration.
- Published under the project-wide continuing publication authorization dated 2026-10-23. Connector used for source/index/records, CLI for unsupported Release/assets and local Git sync. Public preview: live-game hooks, notifications, lifecycle and physical SSD IO remain unverified. No installed DLL or production data modified.


## 2026-10-25 — BGMPlayer 1.1.1.0 public preview

- Release: https://github.com/Roxyz0501/AetherRadio/releases/tag/v1.1.1.0
- ZIP: https://github.com/Roxyz0501/AetherRadio/releases/download/v1.1.1.0/AetherRadio-1.1.1.0.zip
- Source/tag: `97e437493b395739afc2b59a165f6c4a78476341`; ZIP 1,387,473 bytes, 10 files; SHA-256 `FF56CF3B4B75D3674FC377CCBD1956A4033CF6A48F488129CDCB47126510DB98`.
- Main transport now toggles the mini-player beside Repeat, with blue indicating visible. Existing seven-language show/hide tooltips and saved preference are reused.
- Settings use changed-only 60-second saves, logout/normal-exit flush, validated atomic replacement, three valid backups and bounded retries. Oversized-primary recovery preserves the damaged original; disposed players reject late playback calls; direct native BGM scene changes retain reset/fade/volume restoration state.
- Clean Release: zero warnings/errors; 238 managed checks, 256 with offline game data, and 90 isolated ImGui checks passed. All 1,293 installed tracks remain selectable. Seven-language toggle interactions cause zero immediate writes; unchanged navigation causes zero catalogue reads. Synthetic UI: three commits / 1,348 logical payload bytes including fixture.
- Anonymous public repository/icon/ZIP verified (HTTP 200; image/png); downloaded ZIP hash and packaged manifest/license notices matched. Release is public, prerelease=true, draft=false.
- Shared index commit: `ce4fd5551f5f1c47a10bf9ca5d051e830e77b885`. Pinned anonymous index and connector verify 1.1.1.0 and all 14 entries; 13 other entries preserved. Normal raw main initially returned cached 1.1.0.0.
- Publication follows the project-wide standing authorization dated 2026-10-23. GitHub connector used for source/index/records; CLI only for unsupported Release/assets and local Git synchronization. No production configuration or installed DLL replaced. Live-game audio/lifecycle/font-atlas/IME/DPI and physical SSD writes remain unverified.

## 2026-10-25 — Gil Beacon 1.0.0.4 full review fixes

- Release: https://github.com/Roxyz0501/GilBeacon/releases/tag/v1.0.0.4
- ZIP: https://github.com/Roxyz0501/GilBeacon/releases/download/v1.0.0.4/GilBeacon-1.0.0.4.zip
- Source/tag: `90f571762e92d535bc8e84e22d2cf762cf42a166`; ZIP 328,520 bytes, nine allowlisted files; SHA-256 `5DE5C5E1FACA875CFA4082CB1A6E6D9C38BABC1074C97A01B9679C3C472F078D`.
- Fixed stale NPC price after item-sheet exception; displayed item identity and row quality must match; managed highlight failures back off five seconds and stop after three consecutive errors with manual retry; reject non-finite/reversed bounds. Unknown settings schemas block writes rather than restoring older data; backup generation overflow rejected before replacement.
- 33,165 checks passed, including repeated cache/idle/stopped frames and 73 persistence checks. Clean Release zero warnings/errors. Same item read 10,000 times invokes sheet reader once; unchanged configuration writes remain zero. Canonical tabs byte-identical; source/package scans passed. Review details: REVIEW_2026-10-25.md.
- Public repository/icon HTTP200 (image/png), anonymous ZIP hash matched. Index commit `be8393c5e21be7d599bc5eda3785d71c30bc921c`: connector/pinned raw verified1.0.0.4, all13 other entries unchanged. Normal raw main initially cached1.0.0.3.
- Published under standing project update authorization. Source/index/records use connector; CLI only for unsupported Release/assets. No production data or installed DLL modified. Live native row mapping, HQ image state, scrolling/DPI/lifecycle and physical SSD writes remain unverified.


## 2026-10-23 — Bait Beacon 1.0.0.2

- Release: https://github.com/Roxyz0501/BaitBeacon/releases/tag/v1.0.0.2
- ZIP: https://github.com/Roxyz0501/BaitBeacon/releases/download/v1.0.0.2/BaitBeacon-1.0.0.2.zip
- Source/tag: `5144dcff6f7df3d022819c9ba9d8795d006ec964`; ZIP 65,970 bytes, five allowlisted files; SHA-256 `8116DF2EE3BB69A7641DB2F5C0C55383AD726AE4E11B1151080D929A8898BB8E`.
- Inventory drawing and saved-list reads stop after three consecutive failures, use spaced retries, retain valid data and expose manual retry. Settings use 60-second changed-only saves, logout/normal-exit flush, validated atomic replacement, three valid backups and corruption recovery.
- Clean Release: zero warnings/errors; 66 offline checks passed. Eight-hour unchanged simulation: zero writes; 600 edits: one save, 156 logical payload bytes. Lock/partial-write/rename/corruption/disposal checks passed. Canonical standard tabs remain byte-identical. No history store or empty history tab is added.
- Public repository and PNG icon returned HTTP 200 (image/png); anonymous downloaded ZIP hash matched, and package manifest author/version/RepoUrl/IconUrl/license/NOTICE verified. GitHub Release asset digest also matched.
- Shared index registration `f8143ac31e15a0f6768b0d11d890f1933f8ade4a` changes only BaitBeacon, preserving all 12 other entries. Connector reads of commit-pinned and normal main raw URLs both returned all 13 entries and BaitBeacon 1.0.0.2.
- Source/index/record writes use GitHub connector; CLI is used only for unsupported Release/ZIP upload and local Git synchronization. Native in-game rendering and actual logout/shutdown timing remain unverified. No installed DLL or production data modified.

## 2026-10-23 — Character Archive 1.0.0.2 published

- Release: https://github.com/Roxyz0501/CharacterArchive/releases/tag/v1.0.0.2
- ZIP: https://github.com/Roxyz0501/CharacterArchive/releases/download/v1.0.0.2/CharacterArchive-1.0.0.2.zip
- Source/tag: `87269ff30a24618b259e74f624df8492c336f444`. ZIP: 83,152 bytes; SHA-256 `EF65B3527741F6EBAF02F7F63CF55626CD8F8829E5B66A792538F25836BE8724`; four allowlisted runtime/license files.
- Changed-only 60-second settings and character snapshots; logout/normal-shutdown/Dispose flush; atomic validated replacement, three valid backups and recovery. Incomplete capture preserves valid records and stops after three failures with manual retry. Same-character single-flight lookups and shutdown cancellation/drain; existing images survive download failures.
- Clean locked-dependency Release rebuild zero warnings/errors; all core tests and 43 persistence/lifecycle checks passed. Synthetic 600 edits: one save / 238 logical bytes; eight unchanged periods: zero writes. Profiles are snapshots, so daily history and empty HistoryFiles tabs do not apply. Shared templates unchanged.
- Public repository/release/icon HTTP200 (image/png); anonymous ZIP hash and manifest API15/version/author/RepoUrl/IconUrl verified. Shared index `9b0e7c05dfb526041866bd3062e48e315d993572`: connector and pinned raw verified 1.0.0.2; 12 other entries unchanged. Normal raw main initially served cached 1.0.0.1 (max-age=300). The normal main URL was subsequently verified at 1.0.0.2.
- Published on the user's explicit request. Connector used for source/index/state; CLI for unsupported Release/assets and local Git synchronization. Earlier approval-review usage failure was resolved on resume. No installed DLL or live settings replaced. Live-game behavior and physical SSD writes remain unverified; see PERSISTENCE_FIX_REPORT.md.


## 2026-10-23 — Gil Ledger 1.2.0.0 published

- Release: https://github.com/Roxyz0501/MarketLedger/releases/tag/v1.2.0.0
- ZIP: https://github.com/Roxyz0501/MarketLedger/releases/download/v1.2.0.0/MarketLedger-1.2.0.0.zip
- Source/tag: `cc3793df009677db862e0134db7771742a66e3f3`; ZIP 143,099 bytes, 11 allowlisted files; SHA-256 `0A111290BB2269A05B361BE3A3B0DCEB1A6CF98A035DB5CF98D6AA4901ABA017`.
- Changed-only 60-second settings saves, three valid backups and recovery, logout/Dispose flush, incremental daily transaction archive, canonical HistoryFiles tab and bounded retries/manual recovery. Existing SQLite reader compatibility and all-date queries retained.
- 4,241 synthetic/core/native-ImGui lifecycle checks passed; Release build zero warnings/errors. Live-game purchase detection/lifecycle and physical SSD writes remain unverified. Published as a public preview. No installed DLL replacement or production migration performed.
- Anonymous repository/icon HTTP200 (image/png), downloaded ZIP hash and 11-file manifest verified. Shared index commit `edd0dcc20835a705bea9dae6853a93c5ccc97fef`: pinned and normal main URLs both verified at 1.2.0.0; all 12 other entries preserved.
- User explicitly requested publication. GitHub connector used for source/index/state; CLI only for unsupported Release/assets and local Git synchronization.


## 2026-10-23 — Command Atlas 1.1.0.1 public preview

- Published at the user's explicit request. Release: https://github.com/Roxyz0501/CommandAtlas/releases/tag/v1.1.0.1
- ZIP: https://github.com/Roxyz0501/CommandAtlas/releases/download/v1.1.0.1/CommandAtlas-1.1.0.1.zip
- Source/tag commit: `7f14b9d1ff86361039691299facacba1436a1071`.
- ZIP SHA-256: `B6638FD8EAF8C9F6BCA45CF71883042D79357D0074BA736BFB39C928C56A6CF6`.
- Changed-only configuration autosave every 60 seconds, lifecycle flush, three valid backup generations and corrupt-primary recovery. Translation/icon tasks are cancelled and drained before disposal; three consecutive failures stop automatic work until explicit retry.
- Clean Release zero warnings/errors. 402 localization/catalog, 7 icon-cache, 19 feature, 30 persistence/fault/shutdown, and 5,583 isolated UI/glyph/lifecycle checks passed. Synthetic 600 edits coalesced to one 90-byte settings payload; 480 unchanged periods produced zero settings writes. Native game operation and OS/physical SSD I/O remain unverified.
- Public repository/icon/ZIP returned HTTP 200 during release publication; downloaded ZIP matched the hash and eight allowlisted package files retained the author, version, RepoUrl, IconUrl and third-party license.
- Shared index commit: `2f22928d100ccba0589336b56b1c61fb147275fd`. Connector verified 13 entries and Command Atlas 1.1.0.1; twelve other entries unchanged. Normal main URL initially returned stale 1.1.0.0 through CDN.
- Source was published via GitHub connector; Release via CLI. Shared-index connector write failed twice before execution due to changing tool catalog, so CLI performed the guarded update. Earlier automatic approval review was unavailable due to usage limits; no index write occurred then. No installed DLL or production settings were replaced.

## 2026-10-22 — Gil Beacon 1.0.0.3 persistence safeguards published

- Release: https://github.com/Roxyz0501/GilBeacon/releases/tag/v1.0.0.3
- ZIP: https://github.com/Roxyz0501/GilBeacon/releases/download/v1.0.0.3/GilBeacon-1.0.0.3.zip
- Source/tag: `6fb3085f7d2533f7d1fae44c7b7cfb1478ade3ac`; ZIP 323,868 bytes, eight allowlisted files; SHA-256 `7ED050C6A74F77A053AFF8ED25995EE49A1D585FFE81932917178262D5CCE838`.
- 60-second changed-only settings, logout/Dispose flush, atomic validated replacement, three valid backups, corruption recovery and bounded failure/manual retry. NPC calculations and highlight method unchanged. No transaction history or empty HistoryFiles tab.
- 20,133 checks passed (69 persistence); clean Release zero warnings/errors. Unchanged 8-hour simulation zero writes; 600 edits plus logout/Dispose: three commits, 133 logical payload bytes. Canonical tabs byte-identical and source/package scans passed.
- Public repository/icon HTTP200 (image/png); anonymous ZIP hash matched. Shared index commit `0d9b55163d7ae17ad85061f420346407b95f34bd`: pinned URL and connector verified1.0.0.3, all12 other entries preserved. Normal raw main URL initially cached1.0.0.2.
- Published at the user's explicit request. Connector used for source/index/records; CLI only for unsupported Release/asset operations. No production migration or installed-DLL replacement. Live-game lifecycle/rendering and physical SSD writes remain unverified; see PERSISTENCE_VERIFICATION.md.

- 2026-10-23 completion: normal public main index now returns 1.0.0.3 (HTTP 200). Publication records resumed after the prior approval-review usage-limit interruption.

## 2026-10-22 — Market Voyager 1.0.1.9 persistence safeguards

- Release: https://github.com/Roxyz0501/MarketVoyager/releases/tag/v1.0.1.9
- ZIP: https://github.com/Roxyz0501/MarketVoyager/releases/download/v1.0.1.9/MarketVoyager-1.0.1.9.zip
- Source/tag: `b1b5006dd1c9d05082d4ed296c1de6298558ae98`.
- ZIP: 533,402 bytes; SHA-256 `1BF1D910B4E926A9CD0115832A3A4E4C58BA0CECE78FFB67175324542B5E9A30`; nine allowlisted files including PERSISTENCE_NOTES.md.
- Replaced per-frame failure retry and direct UI saves with one 60-second changed-only scheduler, logout/Dispose flush, atomic verified replacement and three valid settings backups. Ordinary edits remain deferred during purchase checkpoints; start/resume flush rule definitions once for referential integrity.
- Separated settings from durable current purchase/sale state, counts, membership and bounded latest-world timestamps. Safety failure blocks buying; corrupted settings backups cannot lower current counts or resurrect deleted rules. No automatic purchase replay after recovery.
- On failure, one alternate-name copy of captured data is attempted; both outcomes and the saved path are shown. Automatic retries stop, including at exit. Explicit retry uses current memory; next-start recovery candidates are validated and offered for explicit settings recovery while retaining current safety state.
- Existing world history is bounded latest-state data (512 worlds per list), not a growing event log. No daily event files or empty HistoryFiles tab added; policy applicability documented locally. Shared specifications/templates were not edited.
- Clean Release zero warnings/errors; 960 core assertions, 548 native checks, 38 persistence fault/lifecycle checks, 1170 UI/glyph/lifecycle checks and 53 renders. Normal synthetic scenario: 15 committed file payloads / 5,234 logical bytes; unchanged intervals and post-dispose writes zero. Actual locks, simulated write/rename/disk-full failures, 10,000 stopped retry frames, recovery, concurrent saves and edit-during-save verified. Canonical tabs and source/package scans passed.
- Public repository/icon HTTP 200 (image/png), anonymous ZIP hash/metadata verified. Shared index `65012db5f46e38ab842a195e951d59c87ada8957`, connector and main/pinned raw verified 1.0.1.9; 12 other entries preserved.
- Published under the chat's standing authorization; the audit handoff itself supplied implementation authorization only. Connector used for supported source/index/record actions, CLI for unsupported release/assets and local sync. No live configuration migration, installed DLL replacement or game input. Actual game logout/exit, dependency cancellation and transactions remain unverified; logical bytes are not physical SSD writes.

## 2026-10-21 — Market Voyager 1.0.1.8 price-check history and market approach

- Release: https://github.com/Roxyz0501/MarketVoyager/releases/tag/v1.0.1.8
- ZIP: https://github.com/Roxyz0501/MarketVoyager/releases/download/v1.0.1.8/MarketVoyager-1.0.1.8.zip
- Source/tag: `7cbc5eb665447263449ba7a39372deee796a9e5f`.
- ZIP: 517,587 bytes; SHA-256 `70FD457DB2988DEAF05491DFE63CDCEA6D0D03652893549A7D170D638CBF3921`; eight allowlisted files.
- Per-list six-hour exclusion defaults on and is independently switchable. Successful price-list checks, including no purchase/no listings, update the cooldown; travel/opening/failed loads do not. Last confirmed purchase is separate. Histories persist in UTC with local-time display and a 512-world bound.
- Current DC first, worlds grouped by DC. Start away from Limsa main aetheryte requests one Lifestream teleport and waits up to 120 seconds. In-tour aetheryte return remains walking. Paused edits apply to remaining worlds while the active same-list visit can continue.
- Market approach temporarily enables vnavmesh camera alignment and restores it on cleanup. The ordinary near-board object handler uses no camera sight check, with targetability and 2m distance guards. No OS foreground/input injection or change to purchase UI routing.
- Clean Release zero warnings/errors; 960 core assertions, 548 native checks, 1074 UI/glyph/lifecycle checks and 46 renders. History/save batching, DC order, teleport IPC, camera error cleanup, ordinary native interaction and seven-language UI verified. Canonical tabs and source/package scans passed.
- Public repository/icon HTTP 200 (image/png); anonymous ZIP hash and metadata verified. Shared index `73742ba66ab0f7b30b076e3ea5835f75ae1ee814`, connector and both main/pinned raw verified 1.0.1.8; 12 other entries preserved.
- Published under standing authorization using connector for source/index/records and CLI only for unsupported release/assets and local history sync. No game input or installed DLL replacement. Actual in-game travel, camera and inactive-window access remain unverified.

## 2026-10-21 — Market Voyager 1.0.1.7 editing while paused

- Release: https://github.com/Roxyz0501/MarketVoyager/releases/tag/v1.0.1.7
- ZIP: https://github.com/Roxyz0501/MarketVoyager/releases/download/v1.0.1.7/MarketVoyager-1.0.1.7.zip
- Source/tag: `31a9d22e36d457494d5a29c2e66783790f1507ba`.
- ZIP: 511,727 bytes; SHA-256 `F5F6C3F93CFBAF547245A2389EDD95A79CEECB1A8FC2B5F07270D181FEEE2E6C`; eight allowlisted files.
- Lists unlock only when fully paused. Resume validates/reloads the selected list, rebuilds additions/deletions/limits/quality, preserves purchased counts and restarts item search from the beginning with fresh listings. Start remains disabled during a paused tour.
- Remaining world itinerary is retained. Aetheryte pause continues toward the queued next world; vendor pause uses updated auto-sell settings/list. Active-list deletion follows the replacement selection. Empty/completed lists end; invalid overlaps stop before further purchase. No return to previously visited worlds.
- Clean Release zero warnings/errors; 943 core assertions, 542 native checks, 1022 UI/glyph/lifecycle checks and 39 renders. Production pause/edit/resume regressions and Japanese paused UI verified. Canonical tabs and source/package scans passed.
- Public repository/icon HTTP 200 (image/png), anonymous ZIP hash and metadata verified. Shared index `16e6a309655541f234ca9ee85e2046e13137b455`, connector and pinned raw verified 1.0.1.7; 12 other entries preserved. Main raw initially cached 1.0.1.6.
- Published under standing authorization using connector for source/index/records and CLI only for unsupported release/assets and local history sync. No game input or installed DLL replacement. Actual in-game resume behavior remains unverified.

## 2026-10-21 — Market Voyager 1.0.1.6 configurable wait and list deletion

- Release: https://github.com/Roxyz0501/MarketVoyager/releases/tag/v1.0.1.6
- ZIP: https://github.com/Roxyz0501/MarketVoyager/releases/download/v1.0.1.6/MarketVoyager-1.0.1.6.zip
- Source/tag: `c665015bbf20f6364c6b64ce1c88481629a510b0`.
- ZIP: 510,515 bytes; SHA-256 `ED285F20C6484BD7CDE69645873D180B17C8D60911847BB71443ABE6C866FCA3`; eight allowlisted files.
- Purchase delay is persisted and editable in Settings, 50–2000ms, default/legacy fallback 100ms, with a reset button. Live changes apply to subsequent purchase scheduling. Checkbox minimum 250ms, inventory reconciliation, error backoffs and timeouts remain.
- List settings offers inline-confirmed whole-list deletion while stopped. Other lists are retained; deleting the final list creates an empty list. Both unresolved purchase/sale ledgers survive deletion and restart until reconciliation.
- Clean Release zero warnings/errors; 943 core assertions, 542 native checks, 1005 UI/glyph/lifecycle checks and 39 renders. Delay bounds/migration/persistence and all five phases at four delays tested; whole-list deletion, pending ledgers and last-list fallback tested. Japanese settings/confirmation images inspected; canonical tabs and source/package scans passed.
- Public repository/icon HTTP 200 (image/png); anonymous ZIP hash/metadata verified. Shared index `de96201b851e54c7abb221758e672bf50c0bc4a3`, connector and pinned raw URL verified 1.0.1.6; 12 other entries preserved. Main raw initially cached 1.0.1.5.
- Published under standing authorization using connector for source/index/records, CLI only for unsupported release/assets and local history sync. No game input or installed DLL replacement. Actual in-game timing remains unverified.

## 2026-10-21 — Market Voyager 1.0.1.5 closer market access and faster purchasing

- Release: https://github.com/Roxyz0501/MarketVoyager/releases/tag/v1.0.1.5
- ZIP: https://github.com/Roxyz0501/MarketVoyager/releases/download/v1.0.1.5/MarketVoyager-1.0.1.5.zip
- Source/tag: `849d2393503c7123d7b09beae18db782f2dcf186`.
- ZIP: 507,988 bytes; SHA-256 `2713D96F7BA13DDE30E9FD6C53DCF15B31CE6D87F58AEC12633F0A1D99820339`; eight allowlisted files.
- Stop within 2m instead of 3m; settle one second and attempt ordinary market interaction up to three times at two-second intervals without renewing the Open timeout.
- Purchase-stage checks/transitions use 100ms; checkbox updates wait 250ms. Removed fixed two-second post-purchase delay. Receipts only wake reconciliation; the exact inventory increase must be observed before the reservation clears, and the next action waits for the purchase dialog to close. No change to normal UI routes, caps, persistence or bounded error retries.
- Clean Release zero warnings/errors; 943 core assertions, 542 native checks, 929 UI/glyph/lifecycle checks and 39 background renders. Scheduler timeout and early-receipt regressions passed. Canonical tabs and source/UTF-8/UTF-16 package scans passed.
- Public repository/icon HTTP 200 (image/png); anonymous ZIP hash and manifest matched. Shared index commit `d39ce50c70cd3319099706165237f8304edc5c9e`, connector, main raw and pinned raw verified 1.0.1.5; 12 other entries preserved.
- Published under standing authorization. Connector used for source/index/records; CLI only for unsupported Release/assets and local history sync. No installed DLL replacement or game input. Actual game position and throughput remain unverified; timing values describe scheduling, not measured purchases per second.

## 2026-10-20 — Market Voyager 1.0.1.4 listing eligibility and walking return

- Release: https://github.com/Roxyz0501/MarketVoyager/releases/tag/v1.0.1.4
- ZIP: https://github.com/Roxyz0501/MarketVoyager/releases/download/v1.0.1.4/MarketVoyager-1.0.1.4.zip
- Source/tag: `9a8b0d93f584d78fe1f00f051122ed4641e16938`.
- ZIP: 507,094 bytes; SHA-256 `00472813E52F1C80C8FBA9C9BD6F96D30C400407DEBA24DEC56FBD79BFE37C08`; eight allowlisted files.
- Search focuses the ordinary input collision node before typing. Already-open matching results advance to eligibility. Pre-dispatch failures no longer exclude the listing or renew the deadline, and perform no reservation disk writes. Last offer/candidate counts are visible.
- Stopped single/bulk deletion retains only unresolved transaction ledgers until reconciliation. List settings keep a fixed anchor. World changes require walking back to Limsa main aetheryte and Lifestream recognition of aetheryte 8; return-to-gateway is false.
- Clean Release zero warnings/errors; 943 core assertions, 542 native checks, 917 UI/glyph/lifecycle checks, 39 renders. Sixty popup frames remained stationary; Japanese image inspected. Canonical tabs and source/UTF-8/UTF-16 package scans passed.
- Public repository/icon HTTP 200 (image/png); anonymous release download matched hash and manifest. Shared index `c9cebfabd3031bbe7761091b828d750e3a8d0d6b`, connector, main raw URL and pinned raw URL verified 1.0.1.4; 12 unrelated entries preserved.
- Published under standing authorization. Connector used for source/index/records; CLI only for unsupported release/assets and local Git synchronization. No installed DLL replacement or game input. Actual in-game purchase/search/walking behavior remains unverified.

## 2026-10-20 — Market Voyager 1.0.1.3 search/confirmation and stopped editing

- Release: https://github.com/Roxyz0501/MarketVoyager/releases/tag/v1.0.1.3
- ZIP: https://github.com/Roxyz0501/MarketVoyager/releases/download/v1.0.1.3/MarketVoyager-1.0.1.3.zip
- Source/tag: `8d31c2778e61e258ce8fd102eeb333871ce3bc8d`.
- ZIP: 504,015 bytes; SHA-256 `21B3E5344B5D05791B61C8B9F4EFC488F7BD0E7BB69378BD81272A326888459D`; eight allowlisted files.
- Search sends the registered TextChanged callback with the normal widget buffers/owner. Pre-OK validation compares the selected listing, not the last-purchase record populated after acceptance. Submission state is persisted before the ordinary OK event; disabled buttons remain disabled.
- Stopping unlocks settings and bulk editing; only deletion/reset of the unresolved row is protected. Owned unsent dialogs are canceled when possible. Stopped inventory reconciliation credits successful purchases; confirmed cancellations and an explicit legacy not-purchased recovery path do not inflate purchased counts. Conservative manual counts do not create resale stock.
- Clean Release zero warnings/errors; 943 core assertions, 534 native ABI/search/selection checks, 847 UI/glyph/lifecycle checks and 38 renders. Inspected Japanese stopped-pending screen. Canonical tabs, source and UTF-8/UTF-16 binary scans passed.
- Read-only installed-client analysis confirmed the late last-purchase update. No game code/disassembly/data redistributed. No game input or installed DLL replacement performed; live-game confirmation remains outstanding.
- Public repo/icon HTTP 200 (image/png); anonymous ZIP hash matched. Shared index commit `16e35611c4e35740ba6e0f5ac371d7b2541b749a` and connector verified 1.0.1.3; 12 other entries preserved. Main raw URL initially cached 1.0.1.2; pinned URL served 1.0.1.3.
- Published under standing authorization. Connector used for source/index/records; CLI only for unsupported Release/assets and local history synchronization.


## 2026-10-20 — Market Voyager 1.0.1.2 search startup fix

- Release: https://github.com/Roxyz0501/MarketVoyager/releases/tag/v1.0.1.2
- ZIP: https://github.com/Roxyz0501/MarketVoyager/releases/download/v1.0.1.2/MarketVoyager-1.0.1.2.zip
- Source/tag: `21840366bae4c505501551f9a0cd1779e87d9e68`.
- ZIP: 500,575 bytes; SHA-256 `11D0900CB8F5B682446EA96422DC6F60EC58AAC7B3EBD39B2C896A1FE8F978A2`; eight allowlisted files.
- Removed the Normal-only gate before name entry; input update precedes the ordinary registered search-button click. Button event lookup skips hover/press and other listeners. Complete matching listings no longer wait on a stale WaitingForListings flag; incomplete/loading UI remains blocked. Reopening the same item preserves the retry budget. Bounded, non-personal diagnostic logging added.
- Clean Release: zero warnings/errors; 931 core assertions, 520 native-layout search/event/readiness regressions, 812 UI/lifecycle/retry checks and 31 background renders. Canonical tabs and source/binary scans passed.
- Public repo/icon HTTP 200 (image/png); anonymously downloaded ZIP hash matched. Shared index commit `164683b44a9161e237d77718d212ded779693ff6` and connector verified 1.0.1.2 with all 12 other entries preserved. A concurrent index update was reread and retained. Main raw URL initially served cached 1.0.1.1; pinned URL served 1.0.1.2.
- Published under standing user authorization. Connector used for source/index/records; CLI only for unsupported Release/assets and local Git synchronization. No installed DLL replacement or game input. The reported live state could not be inspected because no game process was present; actual in-game fix confirmation remains outstanding.


## 2026-10-20 — Gil Beacon 1.0.0.2 materia pricing and incremental highlights

- Release: https://github.com/Roxyz0501/GilBeacon/releases/tag/v1.0.0.2
- ZIP: https://github.com/Roxyz0501/GilBeacon/releases/download/v1.0.0.2/GilBeacon-1.0.0.2.zip
- Source/tag: `9f551ad18feb10805ca0cd98d94cee6100a95232`; ZIP 311,197 bytes; SHA-256 `7CC94A3B230C1EA0459ABC4FF70B6408344448450294DDA60ABF583B5C4A2B85`.
- Materia item category applies the verified rounded-up 10% resale correction: base144 ->159, so price99 plus tax4 yields56. Ordinary qualityless items remain unchanged. Attached materia and special shop bonuses remain excluded.
- Available local rows sorted by price (maximum100); no whole-list count/update wait. Visible row price and quantity must match before immediate calculation/drawing. Cutoff uses greatest possible quality value to retain profitable later HQ rows. No network requests or database writes; one cached sheet row per item change. Limits are code-derived, not measured live.
- Clean Release zero warnings/errors; 20,064 offline checks passed. Canonical tabs byte-identical; source/package credential and local-path scans passed. Seven languages updated; ECommons layout reference documented.
- Public repository/icon HTTP200, image/png; anonymous ZIP hash matched. Index commit `60bd0d3646ab2677685a68fa4e23142fd00bfa8c`, connector and pinned URL verified1.0.0.2, all12 other entries unchanged. Normal main raw URL initially cached1.0.0.1.
- Updated live-game row mapping/speed remains unverified. No installed plugin binary replaced. Connector used for source/index/records; CLI only for unsupported Release/asset publication under standing user authorization.


## 2026-10-20 — Market Voyager 1.0.1.1 registered-list bulk editing

- Release: https://github.com/Roxyz0501/MarketVoyager/releases/tag/v1.0.1.1
- ZIP: https://github.com/Roxyz0501/MarketVoyager/releases/download/v1.0.1.1/MarketVoyager-1.0.1.1.zip
- Source/tag: `13ceec38afa148c1f724abdcc64a85af3edbb8ac`.
- ZIP: 499,075 bytes; SHA-256 `DA60D4EB357BE9DD117608DAE5FA801BD72250880514D9D9D45A0E6EB3447205`; eight allowlisted files.
- Visible Batch edit button above registered items; explicit selected/all-registered scope, including off-page/search-excluded rows. Fields start unchecked and only opted-in fields change. Dedicated NPC pricing also supports both scopes. Purchased and unsold counts preserved.
- Release zero warnings/errors; 931 core assertions, 810 offline UI/glyph/lifecycle/scope checks, 31 renders. Direct editor tested against 45 registered rows; opening it changes no saved values. Canonical shared tabs and source/binary scans passed.
- Public repo/icon HTTP 200, image/png; anonymous ZIP hash matched. Shared index commit `7c6a60057d0df844444ab8c3c37270dabae1c080`: connector/pinned URL verified 1.0.1.1 and all 12 other entries preserved. Normal main URL initially returned cached 1.0.1.0 (HTTP 200).
- Published under the user's standing instruction, connector used for source/index/records and CLI only for unsupported Release/asset operations. Actual game behavior remains unverified. No installed plugin DLL replaced.


## 2026-10-20 — Gil Beacon 1.0.0.1 highlight fix

- Release: https://github.com/Roxyz0501/GilBeacon/releases/tag/v1.0.0.1
- ZIP: https://github.com/Roxyz0501/GilBeacon/releases/download/v1.0.0.1/GilBeacon-1.0.0.1.zip
- Source/tag: `b2cdad035818555fe717df673f7f3facc069c875`; ZIP 309,367 bytes; SHA-256 `732848443AA479DFEFB30BDB08D7B6C1E7BDDBDEE1472CD4D127ED69358D128A`.
- Read-only live diagnostics found WaitingForListings=1 despite a ready addon, 35 listings, matching list count, 10 visible renderers and no pending UI/scroll update. Removed this incorrect gate. Matching counts, addon readiness, pending UI/scroll guards and per-listing item identity remain.
- Clean Release: 0 warnings/errors; 20,049 checks passed including reported 100-gil listing versus 217-gil vendor value (112 gil profit after 5 gil tax), readiness and partial-list rejection. Source/package scans passed. Canonical tabs, HQ pricing and right-side labels preserved.
- Public repository/icon HTTP 200; anonymous ZIP hash matches local. Shared index commit `6cd6cea7d683912886876902d7206e98152cf1bc`; pinned index returns 1.0.0.1. Main raw URL initially cached 1.0.0.0.
- Final in-game rendering after update still awaits user confirmation. No game-memory writes, game input, or installed-DLL replacement performed.
- Connector used for source/index/records; CLI only for unsupported Release/assets.


## 2026-10-20 — Market Voyager 1.0.1.0 public preview

- Published under the user's standing publication instruction. Repository: https://github.com/Roxyz0501/MarketVoyager
- Release: https://github.com/Roxyz0501/MarketVoyager/releases/tag/v1.0.1.0
- ZIP: https://github.com/Roxyz0501/MarketVoyager/releases/download/v1.0.1.0/MarketVoyager-1.0.1.0.zip
- Source/tag commit: `a1d983a9089dd1b0db268d56efd6d5e86b9e8a66`.
- ZIP: 498,021 bytes; SHA-256 `05C4D883CA6BC47067E2C080B4ADA57E5091C083347ED6DF6B186E318333D782`; eight allowlisted files.
- One-item-per-row editable grid, frozen header/name columns, separate simplified Add items tab, compact filters and list-settings popup. Referenced Gil Ledger's table/filter layout concepts (Roxyz0501, MIT); no UI source file copied.
- Persistent top Start / Pause or Resume / Stop controls. Pause waits for an in-flight transaction/movement to resolve; resume excludes paused duration from deadlines and retains the tour cursor.
- Single/selected/all-row price, quantity, quality, NPC-minus-margin price, reset and remove operations. Dedicated NPC batch action preserves quantity limits, quality, purchased counts and sale ledger.
- Release build zero warnings/errors; 931 core assertions, 800 offline ImGui/glyph/lifecycle/controller checks, 30 renders. Production runner safe-boundary pause/resume invoked in offline host. Unchanged rendering saves zero config files.
- Canonical tabs unchanged; source/binary credential and local-path scans passed. Public repo/icon HTTP 200, image/png; anonymous ZIP hash matched.
- Shared index commit `d893ac9d704571a9e53a76c5f0a8e3bcd32386d3`: connector and pinned anonymous URL verified 13 entries with 1.0.1.0; all 12 other entries preserved. Normal main URL initially served cached 1.0.0.0.
- Actual game purchase/sale, pause timing, navigation and DC transfer remain unverified. Preview disclosure and dependency requirements retained. No installed plugin binary replaced.


## 2026-10-20 — Gil Beacon 1.0.0.0 public preview

- Published at the user's explicit request; new standalone plugin, author Roxyz0501, Apache-2.0, Dalamud API 15.
- Repository: https://github.com/Roxyz0501/GilBeacon
- Release: https://github.com/Roxyz0501/GilBeacon/releases/tag/v1.0.0.0
- ZIP: https://github.com/Roxyz0501/GilBeacon/releases/download/v1.0.0.0/GilBeacon-1.0.0.0.zip
- Source/tag commit: `5e3171baa963200b17b925c7d322464a6682aeb0`.
- ZIP: 308,973 bytes; SHA-256 `D3CA336A7FA3E49647B568C8F6B99BFF6595727DF6EDDD99BC7DB7C7B97F341C`.
- Green listing highlights and right-side total profit labels after purchase tax; HQ NPC value includes a 10% bonus rounded upward per unit. Materia/special vendor bonuses and mannequin/set sales excluded. No automated purchase/sale or added market requests.
- Seven UI languages, canonical trailing tabs and original 512x512 PNG icon. Localized font/language utilities adapted from Roxyz0501 Bait Beacon with Apache-2.0 notice.
- Clean Release: 0 warnings/errors after fresh NuGet restore; 20,039 offline arithmetic/localization checks passed. Source/package secret and local-path scans passed. Public anonymous repository and PNG returned HTTP 200 (image/png); public ZIP hash matched local.
- Live-game row mapping, sorting/scrolling, DPI, glyph rendering and NPC receipt totals remain unverified. Right-edge label clipping is disclosed.
- Final anonymous verification: both normal main and commit-pinned index URLs returned HTTP 200 with 13 entries and GilBeacon 1.0.0.0; all 12 prior entries were unchanged.
- Shared index commit: `12f98ee8b970f940831651dc87116e4f8d26fe8a`, adding GilBeacon while preserving all 12 prior entries. Normal raw URL initially cached the previous list.
- Source/index/record writes used the GitHub connector. CLI used for unsupported repository creation, binary icon upload and Release/asset operations. No installed plugin DLL replaced.


## 2026-10-20 — Market Voyager 1.0.0.0 public preview

- Published at the user's explicit request. New independent Dalamud API 15 plugin by Roxyz0501, MIT; separate from Market Sweep.
- Repository: https://github.com/Roxyz0501/MarketVoyager
- Release: https://github.com/Roxyz0501/MarketVoyager/releases/tag/v1.0.0.0
- ZIP: https://github.com/Roxyz0501/MarketVoyager/releases/download/v1.0.0.0/MarketVoyager-1.0.0.0.zip
- Source/tag commit: `7273c1a0e0f09b0e32dbaeee0138659b15395280`.
- ZIP: 493,267 bytes; SHA-256 `260F07DA200C539DF9F2C4CFA0FE0A1C55302C4ECA0BB213F037A2097D18394E`; eight allowlisted files.
- Shopping lists with HQ/NQ/Any, tax-inclusive limits from NPC resale price minus a margin, category/name/price filters, multi-add, batch edits and purchased-count resets. Lifestream/vnavmesh dependency checks.
- Optional NPC resale at a free-slot threshold, including full inventory; returns to the same world's market and resumes. Purchased counts are never reduced by sales. Only fully accounted stacks of confirmed plugin-acquired items are eligible; sale journal is separate by character and quality.
- Normal purchase/sale UI events; no direct purchase packets. Inventory reconciliation, bounded same-listing purchase retries and listing-fetch reopening. Unknown sale outcomes are never automatically retried.
- Release build: zero warnings/errors. 922 core assertions, 772 native ImGui/glyph/lifecycle checks, 28 offline renders. Unchanged views save zero config files. Canonical tab source byte identity, manifest URLs, source/packaged-path and credential-pattern scans verified.
- Actual in-game purchase, sale, warnings, return/resume, navigation and DC transfer are unverified. Cross-logical-DC aetheryte travel needs a compatible Lifestream; explicit public-preview disclosure in manifest, README and Release notes.
- Anonymous public repository and PNG icon HTTP 200; downloaded release ZIP hash matched. Shared index commit `00fcd9575a8e613777d2029cacc2b6f1393d7376`: pinned and normal URLs HTTP 200, 12 entries, correct MarketVoyager version/links; all 11 prior entries preserved.
- Source, icon, index and publication-record writes used the connected GitHub integration. CLI used for unsupported repository creation and Release/asset operations. No installed plugin binaries were replaced.


## 2026-10-18 — Gil Ledger 1.1.0.0 public preview

- Updated at the user's request to support NPC spending and source filtering; renamed display name from Market Ledger to Gil Ledger. Existing InternalName, DLL, repository, config path and database retained for update compatibility. New command /gilledger; /marketledger remains an alias.
- Repository: https://github.com/Roxyz0501/MarketLedger
- Release: https://github.com/Roxyz0501/MarketLedger/releases/tag/v1.1.0.0
- ZIP: https://github.com/Roxyz0501/MarketLedger/releases/download/v1.1.0.0/MarketLedger-1.1.0.0.zip
- Source/tag commit: `8bc13bfe9f471ddecf108cf67dd0899027698b9b`.
- ZIP: 112,141 bytes; SHA-256 `DF857EF33748BC6155512E2378E9032022260075AE367C31C5F06A0A36F4C39C`.
- Ordinary NPC gil-shop requests are reconciled with wallet decreases and matching item gains. Unclassified decreases and exact observed retainer/FC deposits are separate categories. Default totals include confirmed market/NPC purchases only. Source filters apply to history, totals, graphs and CSV; unknown tax is not represented as zero.
- Schema 2 migration creates a pre-migration backup and classifies existing records as market purchases. Seven languages and byte-identical canonical tabs preserved. Event-driven bounded reconciliation; no balance/database polling and no business writes on browsing.
- Clean Release: zero warnings/errors; 774 core and 2,905 native ImGui/glyph/lifecycle checks passed. NuGet restore/audit metadata succeeded with network permission. Public ZIP allowlist, manifest identity/URLs and binary local-path/credential-pattern scan passed.
- Actual in-game purchases, NPC native hook/shop layout, inventory event timing, deposits and live font behavior remain unverified. Special currencies, exchange shops and buyback do not have detailed NPC receipts. Public preview limitations are explicit in README, manifest and Release notes.
- Anonymous public repository and PNG icon HTTP 200 verified. Public ZIP hash matched the local package. Shared index commit `96e7aa75e4a4a2da09f0774c9c7b08daeec7c709`: pinned and normal main URLs both HTTP 200 with Gil Ledger 1.1.0.0 and correct download links; all ten other entries preserved.
- Source/index/publication-record writes used the GitHub connector; CLI used only for unsupported Release/asset operations, repository description and local Git synchronization. No installed plugin DLL was replaced.

## 2026-10-18 — Kuzushi Beacon 1.0.0.1 installation fix

- Release: https://github.com/Roxyz0501/KuzushiBeacon/releases/tag/v1.0.0.1
- ZIP: https://github.com/Roxyz0501/KuzushiBeacon/releases/download/v1.0.0.1/KuzushiBeacon-1.0.0.1.zip
- Source/tag commit: `04c8f20a54ebbde45a98159d08e3ebc59adfe773`.
- ZIP: 56,332 bytes; SHA-256 `F91995785FA1B9F05489EF60784A53A74DF0688924F32955E526A6559C2FA43B`.
- User log confirmed 1.0.0.0 constructor failure: ObjectTable.LocalPlayer was accessed from the installer worker, producing Not on main thread. Now dispatches reconciliation through IFramework.RunOnFrameworkThread; inactive gates skip ObjectTable entirely. Queued work respects disposal and observes failures. No packet/game-action behavior was added.
- Clean Release: zero warnings/errors. 25 new host lifecycle checks invoke the actual Plugin constructor on a worker with thread-enforcing service doubles; 64 prior checks also pass.
- Anonymous repository, PNG icon and release ZIP HTTP 200; downloaded hash matches. Six allowlisted package entries and manifest version/URLs verified. Game installation/overlay acceptance is still unverified; restart clears failed 1.0.0.0 callbacks before update/reinstall.
- Shared index commit: `92319fdad0225f03098d10660decc3ec1470724d`. Connector and anonymous commit-pinned URL verified version 1.0.0.1, preserving all other entries. Normal main URL may lag due to CDN caching.


## 2026-10-18 — PvP Ledger 1.0.0.0 public preview

- Published at the user's explicit request. New standalone plugin, author Roxyz0501, MIT, Dalamud API 15.
- Repository: https://github.com/Roxyz0501/PvPLedger
- Release: https://github.com/Roxyz0501/PvPLedger/releases/tag/v1.0.0.0
- ZIP: https://github.com/Roxyz0501/PvPLedger/releases/download/v1.0.0.0/PvPLedger-1.0.0.0.zip
- Source/tag commit: `9c42ab6f33892c6e4fc20b7c0f5e168aec5e25fa`.
- ZIP SHA-256: `0FC8FA5B00466141750F81600E351BCAAF3365B540158DCD03DCCC02997EFB26` (57,223 bytes, seven allowlisted entries).
- Compact click-through K/D overlay and personal event feed, official final K/D/A, optional Frontline Battle High assist ranges, per-character bounded history, page/event CSV export and opt-in Discord results. Webhook URL encrypted with Windows DPAPI; no real webhook invoked during development.
- Clean Release: zero warnings/errors. 5,829 offline checks passed, including production ImGui rendering, seven-language glyphs, inference, CSV, cache/read counts, notification deduplication and mock HTTP responses. All three native result signatures uniquely matched the installed executable.
- Actual match events, result/gauge offsets, game rendering/DPI and live Discord delivery remain unverified. Public preview limitation is explicit in manifest, README and release notes. Native readers are restricted to game build `2026.10.06.0000.0000`.
- Anonymous repository and PNG icon returned HTTP 200; public ZIP download matched the verified hash. Canonical tab source matched byte-for-byte. Attribution includes wrath16/PvpStats packet layouts, hook signatures and Battle High offset with original MIT license.
- Source/index publication uses the connected GitHub integration; CLI used for unsupported repository creation and Release/asset operations. Existing shared-index entries preserved.
- Final metadata commit: `08b5b7bd561b2c433aef96a7559f417644fbfb92`. Anonymous normal main URL and commit-pinned index now both return HTTP 200 with 11 entries and PvPLedger 1.0.0.0; all ten pre-existing entries preserved.

## 2026-10-18 — Kuzushi Beacon 1.0.0.0 public preview

- Published at the user's explicit request. Initial classification: new standalone plugin; author Roxyz0501; Apache-2.0; Dalamud API 15.
- Repository: https://github.com/Roxyz0501/KuzushiBeacon
- Release: https://github.com/Roxyz0501/KuzushiBeacon/releases/tag/v1.0.0.0
- ZIP: https://github.com/Roxyz0501/KuzushiBeacon/releases/download/v1.0.0.0/KuzushiBeacon-1.0.0.0.zip
- Source/tag commit: `d2300e54bfaa06c5209ebcd669b7218000a3b5d5`.
- ZIP: 55,209 bytes; SHA-256 `13E8F6647A70CE23E3CA56FAD0DF8C795DC733866575C55B9EDD1D59A7914A7B`.
- Local line and overhead marker for the player's own Kuzushi. Independent visibility/colors/alpha, line width, marker size/height, distance and scan interval. No packet/network hooks, game writes or action/target/marker execution. Event-driven suspension outside PvP/on other jobs; default 100 ms scan interval.
- Clean Release zero warnings/errors; 64 managed checks; seven languages, 196 strings, 580 required font codepoints verified. Original 512x512 icon and byte-identical shared tabs. Six allowlisted release entries; author/version/RepoUrl/IconUrl retained.
- Anonymous repository, PNG icon and ZIP HTTP 200; public ZIP hash matched. Native game overlay placement, real status-source behavior and game performance remain unverified and are disclosed in the public preview.
- Shared index registration: `a553a904e21e0fb1475df8f0c2e0754d9cbd0bb8`. Connector and anonymous commit-pinned index verified 10 entries, preserving all 9 existing entries. Normal main URL initially returned a cached 9-entry index.
- Source/icon/index/ledger writes used the connected GitHub integration. CLI used for unsupported repository creation, Release/asset publishing and local Git-object synchronization.


## 2026-10-18 — Market Ledger 1.0.0.0 public preview

- Published at the user's explicit request; new standalone plugin, author Roxyz0501, MIT, Dalamud API 15.
- Repository: https://github.com/Roxyz0501/MarketLedger
- Release: https://github.com/Roxyz0501/MarketLedger/releases/tag/v1.0.0.0
- ZIP: https://github.com/Roxyz0501/MarketLedger/releases/download/v1.0.0.0/MarketLedger-1.0.0.0.zip
- Source/tag commit: `c95ee85a2c2b3b3d43916f6e172e002e4d388045`.
- ZIP SHA-256: `D386B147058E281D1E1F0CBC8E2E012AD98979F99BA72B974A20A710D6B25C88`.
- Per-character confirmed market purchases, retainer names when observed, tax-exclusive/tax/inclusive amounts, search/filter, daily/monthly/cumulative spending graphs and filtered CSV export. Local-only SQLite storage; no companion plugin dependencies. Seven UI languages and exact canonical trailing tabs.
- Clean Release zero warnings/errors; 653 core and 2,468 native ImGui/glyph/lifecycle checks passed. Unchanged views perform zero DB reads/writes; uncached page navigation reads at most 100 rows. In-game purchase/tax/world-travel/live-font acceptance remains unverified and is disclosed in the public prerelease.
- Anonymous repository, PNG icon and ZIP HTTP 200 verified. Downloaded ZIP hash, eight allowlisted entries and manifest author/version/RepoUrl/IconUrl verified.
- Shared index commit: `9a6fad59087a74b6e1f98b36f135d8c832c89c3f`. Connector and anonymous commit-pinned URL verified nine entries and correct download links, preserving all eight existing entries. Ordinary main URL initially served a cached eight-entry index.
- Source/icon/index/record writes used the connected GitHub integration. CLI used only for unsupported repository creation and Release/asset publishing. No installed plugin DLL was replaced.


## 2026-10-18 — BGMPlayer 1.1.0.0 public preview

- Release: https://github.com/Roxyz0501/AetherRadio/releases/tag/v1.1.0.0
- ZIP: https://github.com/Roxyz0501/AetherRadio/releases/download/v1.1.0.0/AetherRadio-1.1.0.0.zip
- Source/tag commit: `b53f098f33176029a9617678715bafd6c4b7c577`.
- ZIP SHA-256: `BB9A19E45C8493694A7CFB5E946E2C2D2B756435CFF3A50C9029C9F7A647AD92`.
- Added mini-player restore/favorite buttons; normal/Savage, alliance and special-content genres; optional suppression of reused audio in later expansion tabs; session-only recent history capped at 30 tracks. Seven-language UI and canonical shared tabs retained.
- Clean Release: zero warnings/errors; 200 managed checks, 218 with four offline game-data languages, and 71 isolated ImGui checks passed. Initial local sheet-service requests reduced from 4,810 to 11; subsequent navigation/filter/history reads and unchanged saves are zero. All 1,293 installed tracks remain available.
- Anonymous repository, PNG icon and ZIP returned HTTP 200. Downloaded ZIP matched the hash; packaged manifest version/author/RepoUrl/IconUrl and required license were verified.
- Shared index commit: `b242aec049c4247441e3c53e5e8954d541830adb`. Both anonymous main and commit-pinned URLs returned HTTP 200, eight entries, version 1.1.0.0 and the new ZIP URL. Seven other plugin entries were unchanged.
- Live-game audio/font-atlas/IME/DPI acceptance remains unverified; release is a public prerelease, not a draft. No installed DLL replacement; previous assets retained. Source/index/ledger writes used the GitHub connector, with CLI only for unsupported release/asset operations and local Git synchronization.

## 2026-10-14 — Command Atlas 1.1.0.0 public preview

- Release: https://github.com/Roxyz0501/CommandAtlas/releases/tag/v1.1.0.0
- ZIP: https://github.com/Roxyz0501/CommandAtlas/releases/download/v1.1.0.0/CommandAtlas-1.1.0.0.zip
- Source/tag commit: `fc79ea7c0899425db8fa21a5b15e5a5d2dba32fb`.
- ZIP SHA-256: `7D2E4012EAA079CB886C7CD3AF42E1F45A23FC4D401BB0BA5890A592A523B1A6`.
- Added per-command execution/copy, editable arguments, help-derived and saved manual subcommands, disabled-plugin exclusion, and optional cached Japanese descriptions through GTranslate 2.4.0 / GoogleTranslator2. User explicitly approved sending descriptions only with translation enabled. Default is off.
- Clean Release: zero warnings/errors; 353 catalog/localization, 7 icon-cache, 19 offline feature/cache and 4,820 isolated ImGui/glyph/lifecycle/access checks passed. Live Google batch translation succeeded (20 feature checks including live); NuGet query reported no known vulnerable dependencies.
- Anonymous repository, PNG icon and ZIP returned HTTP 200. Downloaded ZIP matched the verified hash; eight allowlisted entries include GTranslate DLL and full MIT license. Packaged RepoUrl/IconUrl/version checked; canonical tabs unchanged.
- Shared index commit: `8d5111005795e587f8aee7433dcfc6d071d0ea23`. Eight entries verified at anonymous commit-pinned URL; seven other entries unchanged. Normal main URL initially served cached 1.0.0.0.
- Native game integration remains unverified and disclosed as a public preview. No installed plugin DLL was replaced. Source/index writes used the GitHub connector; CLI was used for unsupported Release publishing and Git synchronization.

## 2026-10-12 BGMPlayer 1.0.0.1

- Release: https://github.com/Roxyz0501/AetherRadio/releases/tag/v1.0.0.1
- ZIP: https://github.com/Roxyz0501/AetherRadio/releases/download/v1.0.0.1/AetherRadio-1.0.0.1.zip
- Source commit: `1559df1a627c03ec2105d84a03c40e50e208bf90`; SHA-256: `BDC3970FDCA020CC10EA0B357D34A8023C9B16DBAD10C5263B31F9B1F0CA121E`.
- Copied the latest canonical StandardPluginTabs.cs exactly and call DrawStandardTrailingTabs once after Library. The unchanged visible order is Library, Settings, Language settings, Support. Saved language, lists, playback settings and direct installer Settings access are retained.
- Clean Release build: zero warnings/errors. 170 managed and 59 isolated ImGui checks passed, including actual tab IDs/positions and direct Settings access in all seven languages. Navigation causes zero extra catalogue reads; unchanged views cause zero saves.
- Anonymous repository, image icon and ZIP returned HTTP 200. The downloaded ZIP hash, manifest identity/version/URLs and license notices were verified. Game font-atlas, IME/DPI and native audio acceptance remain unverified; this is a public preview.
- Shared registration `7ac6802cf3fae1674b9e72f42ef829d8065eed04` updated only AetherRadio, preserving all six other entries after incorporating concurrent updates. The anonymous commit-pinned index returned HTTP 200 with seven entries and version 1.0.0.1. The normal main URL initially returned cached 1.0.0.0.
- Existing 1.0.0.0 release assets were retained unchanged. Source/index/ledger writes use the GitHub connector; CLI is used only for unsupported Release/asset operations and local Git-object synchronization.

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

## 2026-10-14 Command Atlas 1.0.0.0

- Explicitly published at the user's request; author Roxyz0501.
- Repository: https://github.com/Roxyz0501/CommandAtlas
- Release: https://github.com/Roxyz0501/CommandAtlas/releases/tag/v1.0.0.0
- ZIP: https://github.com/Roxyz0501/CommandAtlas/releases/download/v1.0.0.0/CommandAtlas-1.0.0.0.zip
- Source/tag commit: `404b4dd0daa575f7b9b5fa1fe46d0d91244caa0f`.
- ZIP SHA-256: `85BA8AA6560BB7146A92EA5825083046721CEA2B3ABA5134169C68A372E919AC`.
- Anonymous repository, PNG icon and Release ZIP returned HTTP 200. Downloaded ZIP hash, six package entries, author, version, RepoUrl and IconUrl verified.
- Shared registration commit: `12ed63f569529ab2b6f5ffa964c7434fc410a73f`. Eight entries verified through the connector and anonymous commit-pinned index; the seven existing entries are unchanged. The anonymous normal main URL also returned HTTP 200 with all eight entries and Command Atlas 1.0.0.0 after the initial stale CDN response refreshed.
- Clean Release zero warnings/errors; 213 catalog/localization checks, 7 cache checks and 3,573 isolated ImGui/glyph/copy/lifecycle/access checks passed. UI-test NuGet vulnerability feed remained unreachable (NU1900); not represented as a successful vulnerability audit.
- Native game operation and actual installed-plugin icon/grouping integration remain unverified and are disclosed in README/Release notes. No installed plugin DLL was replaced.
- GitHub connector used for source/icon/index writes and verification. CLI used only for unsupported repository creation/Release asset publishing and local Git synchronization.

