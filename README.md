# TRON.NX

[![TRON.NX](https://img.shields.io/badge/TRON.NX-Framework-blue)](https://github.com/TERRA-TECH-SYSTEMS/tron-nx)
[![Based on Electron](https://img.shields.io/badge/Based%20on-Electron-47848F)](https://electronjs.org)
[![TerraTech Systems](https://img.shields.io/badge/TerraTech-Systems-orange)](https://github.com/TERRA-TECH-SYSTEMS)

**TRON.NX** — **T**uned **R**untime **O**ptimized **N**ative e**X**tension

TerraTech Systems' cross-platform desktop application framework—a performance-optimized fork of [Electron](https://github.com/electron/electron) with enterprise features and Apple Silicon optimization.

---

## Why TRON.NX?

| Feature | Electron | TRON.NX |
|---------|----------|---------|
| Apple Silicon | ✓ | ✓ Optimized |
| Enterprise Signing | Manual | Integrated |
| TerraTech Integration | - | Native |
| Stability Patches | Upstream | Applied |
| Long-term Support | Community | TerraTech |

TRON.NX maintains full compatibility with Electron while adding:
- **Performance tuning** for Apple Silicon M-series processors
- **Stability patches** (e.g., fontations rendering fixes)
- **Enterprise code signing** integration
- **TerraTech ecosystem** compatibility

---

## Installation

### Using npm

```sh
# Install TRON.NX as a development dependency
npm install @terratech/tron-nx --save-dev
```

### Using pre-built binaries

Download from [Releases](https://github.com/TERRA-TECH-SYSTEMS/tron-nx/releases).

---

## Platform Support

| Platform | Architecture | Status |
|----------|--------------|--------|
| macOS | ARM64 (Apple Silicon) | ✓ Primary |
| macOS | x64 (Intel) | ✓ Supported |
| Windows | x64 | ✓ Supported |
| Linux | x64 | ✓ Supported |

---

## Version Scheme

TRON.NX follows Electron versioning with a TerraTech suffix:

```
{electron-version}-tron.{patch}
```

Examples:
- `40.0.0-tron.1` — First TRON.NX release based on Electron 40.0.0
- `40.0.0-tron.2` — Second patch with TerraTech-specific fixes

---

## Applications Built on TRON.NX

| Application | Description | Status |
|-------------|-------------|--------|
| [CodeEX](https://github.com/TERRA-TECH-SYSTEMS/codex) | AI-integrated IDE | Active |
| Terra-Tron | Desktop app runtime | Active |
| Charta Desktop | Collaboration client | Planned |
| GIXSIS Terminal | AI assistant interface | Planned |
| VisionVI Desktop | Video communication | Active |

---

## Building from Source

### Prerequisites

- macOS 12.0+ or equivalent
- Xcode Command Line Tools
- Python 3.11+
- Node.js 20.x
- ~50GB disk space

### Quick Start

```sh
# Clone the repository
git clone https://github.com/TERRA-TECH-SYSTEMS/tron-nx.git
cd tron-nx

# Bootstrap the build environment
./script/bootstrap.py

# Build
./script/build.py -c Release
```

For detailed instructions, see [Build Instructions](docs/development/build-instructions.md).

---

## Contributing

TRON.NX is maintained by TerraTech Systems. We welcome contributions that align with our goals:

1. Performance improvements
2. Stability patches
3. Enterprise feature enhancements
4. Documentation improvements

Please read our [Contributing Guide](CONTRIBUTING.md) before submitting PRs.

---

## Upstream Sync

TRON.NX regularly syncs with upstream Electron to incorporate:
- Security patches
- Chromium updates
- Node.js updates
- Bug fixes

Current base: **Electron v40.0.0** (Chromium 145, Node.js 22)

---

## License

TRON.NX is based on [Electron](https://github.com/electron/electron), licensed under the [MIT License](LICENSE).

TerraTech-specific additions are also MIT licensed.

When using Electron logos, make sure to follow [OpenJS Foundation Trademark Policy](https://trademark-policy.openjsf.org/).

---

## Organization

**TerraTech Systems** delivers intelligent enterprise platforms that transform how organizations collaborate, communicate, and create.

Technology built on the **Triple A's**:
- **Ancestral** wisdom
- **Augmented** capability
- **Authentic** solutions

---

[![GitHub](https://img.shields.io/badge/GitHub-TERRA--TECH--SYSTEMS-181717?logo=github)](https://github.com/TERRA-TECH-SYSTEMS)

*TRON.NX — Powering the next generation of desktop applications*
