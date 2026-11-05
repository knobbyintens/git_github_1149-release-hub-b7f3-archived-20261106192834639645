# Copperleaf Desktop — Release Notes

All notable changes to Copperleaf Desktop are documented here.
Sections are ordered newest first; each released version links back to the
issue tracker entries that shipped with it.

## Unreleased

- Restore workspace tab pinning (#101)
- Search field crashes on empty query (#102)
- Rewrite onboarding checklist copy (#103)
- Realtime collaboration cursors (#104)
- Deduplicate sync jobs after reconnect (#105)
- Offline merge overwrites local edits (#106)
- CSV export for activity log (#107)
- Telemetry collector v2 migration (#108)
- Dark mode flicker on startup (#109)
- Update export dialog tooltips (#110)
- Custom keyboard shortcut editor (#111)
- Harden archive import path checks (#112)
- Stable/beta update channel toggle (#113)
- Diagnostics bundle should include sync logs (#114)
- License banner uses old brand colors (#115)
- Settings v3 migration guide (#116)
- Flaky Windows CI packaging step (#117)

## v4.2.0 — 2026-09-18

- Restored keyboard shortcuts after the editor rewrite (#142)
- Reduced cold start time on workspaces with more than 10,000 notes (#148)

### Maintenance

- Upgraded the packaging toolchain to Node 22 (#151)
- Dropped support for macOS 12 (#154)

## v4.1.0 — 2026-08-05

- Added multi-window support for notebooks (#118)
- Fixed tab ordering when reopening a session (#121)

### Maintenance

- Replaced the legacy icon set (#126)

## v4.0.0 — 2026-06-22

- Rebuilt the sync engine on the new storage layer (#63)
- Migrated the settings schema to version 3 (#67)

## v3.9.0 — 2026-04-11

- Added command palette search across all notebooks (#34)
- Fixed the export dialog freezing on large selections (#37)
