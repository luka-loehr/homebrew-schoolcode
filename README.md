# homebrew-schoolcode

Homebrew tap for [SchoolCode](https://github.com/luka-loehr/schoolcode) - Automated developer tool deployment for macOS Guest accounts.

## Installation

### Quick Install (Recommended)

```bash
brew tap luka-loehr/schoolcode && brew install schoolcode
```

Or use the auto-tap format (taps automatically):

```bash
brew install luka-loehr/schoolcode/schoolcode
```

### What Gets Installed

- `schoolcode` - Main command-line tool
- All SchoolCode scripts and utilities
- Automatic setup of Guest account tools

### Post-Installation

After installation, SchoolCode will automatically:
- Run compatibility checks
- Perform system repairs if needed
- Install development tools (Git, Python, Node.js, etc.)
- Set up Guest account with all tools

You can check status with:
```bash
sudo schoolcode --status
```

## Manual Installation Steps

If you prefer step-by-step:

```bash
# 1. Add the tap
brew tap luka-loehr/schoolcode

# 2. Install SchoolCode
brew install schoolcode

# 3. Check installation status
sudo schoolcode --status
```

## Uninstallation

```bash
brew uninstall schoolcode
```

This will automatically run cleanup before removing files.

## Updating

```bash
brew upgrade schoolcode
```

## Documentation

- **Main Repository:** https://github.com/luka-loehr/schoolcode
- **Issues:** https://github.com/luka-loehr/schoolcode/issues
- **Releases:** https://github.com/luka-loehr/schoolcode/releases

## License

Apache-2.0 - See the [main repository](https://github.com/luka-loehr/schoolcode) for details.
