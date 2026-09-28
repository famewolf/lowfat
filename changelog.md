# Changelog — fork history (ours + upstream)

This fork of [zdk/lowfat](https://github.com/zdk/lowfat) carries local changes that are not (yet) in upstream.

**Attribution key: [US] = authored by the fork owner (famewolf); [UPSTREAM] = authored by the upstream project (zdk / outside contributors).**

This file is kept current automatically: the fork owner's daily upstream-sync job regenerates it from each branch's `git log upstream/main..<branch>` (our changes) plus the recent upstream `main` history, so it stays accurate even after a rebase or sync from upstream.

## Our changes — not yet in upstream [US]

| Branch | Commit | Date | Change | Submitted as | Status (2026-09-28) |
|---|---|---|---|---|---|
| `fix/opencode-v2-plugin` | [`41df350`](https://github.com/famewolf/lowfat/commit/41df350) | 2026-09-26 | Support the OpenCode v2 plugin API via install-time version detection — `lowfat opencode` works on both opencode 1.x and 2.0.x (v1/v2 plugin loaders, `execute.before` hook port) | [zdk/lowfat#20](https://github.com/zdk/lowfat/issues/20) (issue with full change detail; PR offered) | OPEN — awaiting maintainer response |

## Our changes — merged into upstream [US]

| PR | Merged upstream as | Date | Change |
|---|---|---|---|
| [zdk/lowfat#19](https://github.com/zdk/lowfat/pull/19) | `3a0de90` (squash) | 2026-09-17 | run embedded plugin under Node (Electron/desktop), not just Bun |

## Upstream activity — recent `main` history [UPSTREAM]

| Commit | Author | Date | Change |
|---|---|---|---|
| `a17b3e0` | zdk | 2026-09-24 | chore: bump version to 0.8.1 |
| `3a0de90` | famewolf | 2026-09-17 | fix(opencode): run embedded plugin under Node (Electron/desktop), not just Bun (#19) — *our contribution* |
| `d1d0b5c` | zdk | 2026-07-08 | docs: update README |
| `b9f6f99` | zdk | 2026-06-19 | chore: bump version to 0.8.0 |
| `827bd39` | zdk | 2026-06-19 | fix: reject absolute include paths |
| `c92d42b` | zdk | 2026-06-18 | docs: mention include in lf-filter DSL overview |
| `38b3628` | zdk | 2026-06-18 | docs: add runnable include example + e2e test |
| `44d01fd` | zdk | 2026-06-18 | feat: add `include` directive for .lf — share macros across filters |
| `3a6d2a4` | zdk | 2026-06-16 | chore: bump version to 0.7.2 |
| `220dd7b` | Di Warachet S. | 2026-06-16 | fix: ultra Python collapse leaks dedented docstrings (#13) |
| `2bde1b1` | zdk | 2026-06-16 | fix: release pipeline publishes lowfat-compress + idempotent re-runs |
| `128c528` | zdk | 2026-06-16 | chore: bump version to 0.7.0 |

*Rows authored by `famewolf` are our merged contributions (see the table above); all other rows are upstream authors' work — not fork changes.*

## Notes

- Default branch `main` carries docs-only commits (this changelog) ahead of upstream `main`; no code ahead/behind as of 2026-09-28 (upstream unchanged at `a17b3e0`).
- A canonical copy of this changelog is kept by the fork owner (`memory/fork-changelogs/famewolf__lowfat.md`) so the record survives a destructive fork reset; the sync job restores it if a sync removes it from the fork.
