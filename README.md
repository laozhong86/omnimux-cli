# omnimux-cli

**Public binary release surface** for the [OmniMux](https://geminix.cc) user CLI.

| | |
|--|--|
| Install (macOS / Linux) | `curl -fsSL https://geminix.cc/install.sh \| bash` |
| npm | `npm i -g @omnimux/cli` |
| Source of truth | Private monorepo `laozhong86/OmniMux` path `cli/` |
| This repo | GitHub **Releases** only (binaries, checksums, install script) |

Do not open feature PRs here against application source — develop in the OmniMux monorepo.

## Assets

Release tags match monorepo tags: `cli-vX.Y.Z`.

| File | Platform |
|------|----------|
| `omnimux-darwin-arm64` | macOS Apple Silicon |
| `omnimux-darwin-x64` | macOS Intel |
| `omnimux-linux-x64` | Linux x86_64 |
| `omnimux-windows-x64.exe` | Windows x64 |
| `SHA256SUMS` | Checksums |
| `install.sh` | Installer script |

## License

AGPL-3.0. OmniMux is a fork of [new-api](https://github.com/QuantumNous/new-api) by QuantumNous; attribution is preserved.
