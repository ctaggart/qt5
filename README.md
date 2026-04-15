# Qt Static Libraries

Pre-built static Qt libraries for use with `zig build`.
Published as GitHub releases so `build.zig.zon` can depend on them.

## Platforms

| Target | Runner |
|--------|--------|
| x86_64-windows-msvc | windows-latest |
| x86_64-linux-gnu | ubuntu-24.04 |
| aarch64-macos | macos-14 |

## Modules Included

- **qtbase**: Core, Gui, Widgets, Xml, Network
- **qtmultimedia**
- **qtsvg**

## Usage

Download the release tarball for your platform from
[Releases](https://github.com/ctaggart/qt5/releases).

## Building

Static Qt libraries are built via GitHub Actions:

1. **Build**: Actions → Build Static Qt → Run workflow
2. **Publish**: Actions → Publish Qt Release → Run workflow (provide build run ID)

## License

Qt is available under GPL v3 / LGPL v3 / commercial licenses.
Static linking requires GPL v3 or a commercial license.
