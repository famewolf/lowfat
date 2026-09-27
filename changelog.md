# Changelog — local changes in this fork

This fork of [zdk/lowfat](https://github.com/zdk/lowfat) carries local changes that are not (yet) in upstream. This file is kept current automatically: the fork owner's daily upstream-sync job regenerates it from each branch's `git log upstream/main..<branch>` plus the status of the corresponding upstream submissions, so it stays accurate even after a rebase or sync from upstream.

## Not yet merged upstream

| Branch | Commit | Date | Change | Submitted as | Status (2026-09-27) |
|---|---|---|---|---|---|
| `fix/opencode-v2-plugin` | [`41df350`](https://github.com/famewolf/lowfat/commit/41df350) | 2026-09-26 | Support the OpenCode v2 plugin API via install-time version detection — `lowfat opencode` works on both opencode 1.x and 2.0.x (v1/v2 plugin loaders, `execute.before` hook port) | [zdk/lowfat#20](https://github.com/zdk/lowfat/issues/20) (issue with full change detail; PR offered) | OPEN — awaiting maintainer response |

## Merged into upstream (no longer local-only)

| Change | Merged upstream as |
|---|---|
| node compatibility fix (PR #19) | zdk/lowfat `3a0de90` (squash-merged); `main` in this fork is already synced with upstream `main` |

## Notes

- Default branch `main` tracks upstream `main` exactly (0 ahead / 0 behind as of 2026-09-27).
- A canonical copy of this changelog is kept by the fork owner (`memory/fork-changelogs/famewolf__lowfat.md`) so the record survives a destructive fork reset; the sync job restores it if a sync removes it from the fork.
