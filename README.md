# Moderne CLI releases

The Moderne CLI is a tool that allows you to build and publish [Lossless Semantic Tree](https://docs.moderne.io/concepts/lossless-semantic-trees) (LST) artifacts to an artifact repository of your choosing.

## Installation

### Homebrew (macOS/Linux)

```bash
# Stable releases
brew install moderneinc/moderne/mod

# Beta releases (latest pre-release)
brew install moderneinc/moderne/mod --head
```

### Chocolatey (Windows)

```powershell
# Stable releases
choco install mod

# Beta releases
choco install mod-beta
```

### Direct download

Download the latest release for your platform:

- **Linux**: [moderne-cli-linux](https://github.com/moderneinc/moderne-cli-releases/releases/latest/download/moderne-cli-linux)
- **macOS**: [moderne-cli-macos](https://github.com/moderneinc/moderne-cli-releases/releases/latest/download/moderne-cli-macos)
- **Windows**: [moderne-cli-windows.exe](https://github.com/moderneinc/moderne-cli-releases/releases/latest/download/moderne-cli-windows.exe)

Archive formats are also available:
- [moderne-cli-linux.tar.gz](https://github.com/moderneinc/moderne-cli-releases/releases/latest/download/moderne-cli-linux.tar.gz)
- [moderne-cli-macos.tar.gz](https://github.com/moderneinc/moderne-cli-releases/releases/latest/download/moderne-cli-macos.tar.gz)

## Release process

### Pre-releases

Pre-releases are available through:
- Homebrew head formula (`mod --head`)
- Chocolatey beta package (`mod-beta`)
- Direct download from the releases page

### Stable releases

Stable releases are promoted from pre-releases and become the default installation for package managers and the `/releases/latest/` download URLs.

## Getting started

After installation, verify the CLI is working:

```bash
mod --version
```

For usage instructions and documentation, visit the [Moderne CLI documentation](https://docs.moderne.io/user-documentation/moderne-cli).

## Support

For issues and questions:
- [Documentation](https://docs.moderne.io/user-documentation/moderne-cli)
- Email: support@moderne.io
