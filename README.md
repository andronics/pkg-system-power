# Power Management - Battery, brightness, and power control

**Package**: `@system/power`
**Version**: 0.1.0
**Repository**: `pkg-system-power`

## Overview

Power Management - Battery, brightness, and power control

## Installation

### Prerequisites

This package requires the following external commands:

- `bspc`
- `systemctl`

### Using pkg-cli

```bash
# Install from GitHub
pkg-cli install @system/power

# Or install from local source
cd ~/.pkgs
stow power
```

## Usage

### System Integration

This package provides system integration for power management - battery, brightness, and power control.


## Configuration

Configuration files are typically stored in:
- `~/.config/power/` - User configuration
- `~/.local/share/power/` - Application data

## Uninstallation

```bash
# Using pkg-cli
pkg-cli uninstall @system/power

# Or manual unstow
cd ~/.pkgs
stow -D power
```

## Development

See [CLAUDE.md](CLAUDE.md) for development guidelines and AI assistance instructions.

## License

MIT License - See [LICENSE](LICENSE) file for details.

## Support

- **Issues**: [GitHub Issues](https://github.com/andronics/pkg-system-power/issues)
- **Discussions**: [GitHub Discussions](https://github.com/andronics/pkg-system-power/discussions)
- **Documentation**: [pkgs ecosystem docs](https://github.com/andronics/.pkgs)

## Version History

See [CHANGELOG.md](CHANGELOG.md) for version history.
