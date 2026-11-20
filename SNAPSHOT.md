# Frozen foundation snapshot

This repository preserves neo v0.1.0-foundation as a standalone source snapshot.
It has one initial commit, its own release, and no imported development history.
The repository is archived after publication to keep this baseline fixed.

Active development: https://github.com/neo-platform-organization/neo

Original source commit: 32694b25348131165d3e116df74cee96cd9c7691
Original source tag: v0.1.0-foundation
Original release: https://github.com/neo-platform-organization/neo/releases/tag/v0.1.0-foundation
Snapshot date: 2026-11-21

Runtime sources, image, tests, license, and technical guides match that source
commit. This repository adds this provenance file and a frozen-snapshot notice
to README.md. Its release archives are generated from its own commit.

Clean Windows/Linux acceptance suites and standalone x86_64 surface/CLI boot
tests passed before the source baseline was published. This remains a
foundation prerelease, not a completed OS. General asynchronous graph I/O,
atomic whole-image checkpointing, and the documented standalone drivers remain
unfinished. Refer to the included release notes and build guide.

No generated build output, caches, credentials, local exercise data, or research
corpus is included. Rebuild using the root Makefile.
