# Homebrew Tap for Stack To Date CLI

Official Homebrew tap for the [Stack To Date](https://stacktodate.club/) command-line interface.

## About Stack To Date

[Stack To Date](https://stacktodate.club/) is a service that helps development teams track technology lifecycle statuses and plan for end-of-life (EOL) upgrades.

## Installation

```bash
brew tap stacktodate/homebrew-stacktodate
brew install stacktodate
```

## Updating

To update to the latest version:

```bash
brew upgrade stacktodate
```

## Uninstalling

```bash
brew uninstall stacktodate
brew untap stacktodate/homebrew-stacktodate
```

## Usage

After installation, you can use stacktodate:

```bash
stacktodate --help
```

For detailed usage instructions, visit the [Stack To Date CLI repository](https://github.com/stacktodate/stacktodate-cli).

## Quick Start

1. Initialize your project's tech stack:
   ```bash
   stacktodate init --name "My Project"
   ```

2. Push to Stack To Date:
   ```bash
   export STD_TOKEN=your_token_from_stack_to_date
   stacktodate push
   ```

## Links

- **Stack To Date Website**: https://stacktodate.club/
- **CLI Repository**: https://github.com/stacktodate/stacktodate-cli
- **Releases**: https://github.com/stacktodate/stacktodate-cli/releases

## Support

For issues or questions about the CLI, visit the [issue tracker](https://github.com/stacktodate/stacktodate-cli/issues).

For issues with Stack To Date service, visit [stacktodate.club](https://stacktodate.club/).

## License

MIT License — See [LICENSE](https://github.com/stacktodate/stacktodate-cli/blob/master/LICENSE) in the main repository for details.
