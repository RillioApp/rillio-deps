# rillio-deps

Pinned third-party binaries that Rillio's CI bundles. Upstream sources prune
old builds (shinchiro/mpv-winbuild-cmake keeps only its ~30 newest nightlies),
so each pinned build Rillio ships is mirrored here as a release asset and CI
verifies it by sha256.

## libmpv-20260610

`libmpv-2.dll`, extracted unmodified from
`mpv-dev-x86_64-20260610-git-304426c.7z` (archive sha256
`8cbb25ea784f01afbb3f904217cab1317430a8bcfd5680fd827a866367f71cc9`) of
[shinchiro/mpv-winbuild-cmake](https://github.com/shinchiro/mpv-winbuild-cmake)
release `20260610`. Reports `mpv v0.41.0-744-g304426c39`.

License: GPL (mpv and the libraries linked into this build). Source: mpv at
commit [304426c39](https://github.com/mpv-player/mpv/commit/304426c39) and the
build recipe at shinchiro/mpv-winbuild-cmake.
