# ctem-scan-target

Fixture repository for the [ctem-platform](https://github.com/langell/ctem-platform)
scanners and discovery connectors. The dependency set is **deliberately outdated**
(express 4.17.1, qs 6.7.0, lodash 4.17.15, minimist 1.2.5 — all with known,
long-fixed advisories) so scans produce predictable findings.

Do not deploy anything from this repository. Do not "helpfully" upgrade the
dependencies — stale pins are the entire point.

Used for:
- GitHub discovery connector integration tests (repo inventory)
- SCA lockfile resolution (`package-lock.json` is a real npm lockfile)
- End-to-end scan verification
