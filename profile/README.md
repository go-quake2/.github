<p align="center"><img src="https://raw.githubusercontent.com/go-quake2/brand/main/social/go-quake2.png" alt="go-quake2" width="720"></p>

# go-quake2

**Pure-Go Quake II (id Tech 2, 1997) — reserved.**

This organization is **reserved** for the eventual pure-Go port of
[Quake II](https://en.wikipedia.org/wiki/Quake_II) (id Tech 2, 1997),
sibling of [`go-quake1`](https://github.com/go-quake1) (id Tech 1) and
[`go-quake3`](https://github.com/go-quake3) (id Tech 3).

The work has not started; the org is staked out so the
`go-quake{1,2,3}` family naming holds together. Watch
[`go-quake1`](https://github.com/go-quake1) for the active engine
work — Q2 will pick up the same discipline once the Q1 port reaches
the playable bar.

## Planned reference

[`yquake2`](https://github.com/yquake2/yquake2) — the maintained
upstream fork of the id Software 1997 release, GPL-2.0. Same hand-
port-from-reference pattern as `go-quake1` ←
[tyrquake](https://disenchant.net/tyrquake/).

## Planned standards

Same as the [go-quake1](https://github.com/go-quake1) family:
pure Go (`CGO_ENABLED=0`), 100% statement coverage, reference-mirror
traceability, the godoom provable-test 4-gate protocol carried forward,
6-arch CI (`amd64` · `arm64` · `riscv64` · `loong64` · `ppc64le` ·
`s390x`), BSD-3 wrapper + GPL-2.0 engine carve-out.
