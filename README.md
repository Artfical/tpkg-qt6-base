# qt6-base

Qt 6.8.2 base: Core, Gui, Widgets, Network, Xml, Sql, Concurrent, PrintSupport; platforms xcb (the X server of the xorg package: tos-x), linuxfb, offscreen; with headers, qmake, moc, uic, rcc and CMake support to build Qt programs with gcc

A package for [tOS](https://github.com/Artfical/tOS), installed with `tpkg`:

```
sudo tpkg install qt6-base
```

| | |
|---|---|
| Version | 6.8.2-2 |
| Licence | LGPL-3.0-only OR GPL-2.0-only OR GPL-3.0-only (Qt), with bundled MIT, BSD, Zlib, libpng, IJG licensed parts |
| Upstream | https://www.qt.io |
| Needs | [`xorg`](https://github.com/Artfical/tpkg-xorg), [`xcb-libs`](https://github.com/Artfical/tpkg-xcb-libs), [`xcb-util`](https://github.com/Artfical/tpkg-xcb-util), [`xkbcommon`](https://github.com/Artfical/tpkg-xkbcommon), [`fontconfig`](https://github.com/Artfical/tpkg-fontconfig), [`fonts-dejavu`](https://github.com/Artfical/tpkg-fonts-dejavu), [`expat`](https://github.com/Artfical/tpkg-expat) |
| Needs tOS build | 618 or newer |
| Size | 26043671 bytes (80903128 unpacked) |
| SHA-256 of the `.tpkg` | `e69f7d041aaf1d05a5a2b74509f4d340248cdd1147cfa463081350d344915ced` |

## Commands it adds

| Command | Runs |
|---|---|
| `qmake` | `bin/qmake` |
| `qmake6` | `bin/qmake6` |
| `qtpaths6` | `bin/qtpaths6` |
| `qt-cmake` | `bin/qt-cmake` |
| `moc` | `libexec/moc` |
| `uic` | `libexec/uic` |
| `rcc` | `libexec/rcc` |

## Download

The package file (`qt6-base-6.8.2-2.tpkg`) and the sources it was built from are the assets of the
[v6.8.2-2 release](https://github.com/Artfical/tpkg-qt6-base/releases/tag/v6.8.2-2).
Git holds only the text: `meta.json`, the licences and `NOTICE.txt` (how it was built and what was changed).

Sources in the release:
- `qtbase-everywhere-src-6.8.2.tar.xz`

Check a download: `sha256sum qt6-base-6.8.2-2.tpkg` must give the hash above.

## Signatures

Packages are signed by Artfical's package server (Ed25519) and tOS checks the signature before it installs one.
The signature is made when the server hands a package out, so it is not kept here, and the signing key is never published.
`tpkg install` is the supported way to install; a `.tpkg` taken from here has the hash above but not the server's signature.

## Licence

The package is made of other people's software, under their licences: LGPL-3.0-only OR GPL-2.0-only OR GPL-3.0-only (Qt), with bundled MIT, BSD, Zlib, libpng, IJG licensed parts. The licence texts are in this
repository (`LICENSE*`, `UNLICENSE`), and `NOTICE.txt` says how it was built. The sources above are the
corresponding source. `meta.json` and this README are free to copy.

Package problems (build, files, versions): open an issue here. Problems in the software itself belong upstream.
Security reports: see [SECURITY.md](https://github.com/Artfical/tOS/blob/main/SECURITY.md).
