# Helix Themes Chooser

Preview and compare [Helix](https://helix-editor.com/) editor themes with code snippets.

**[View the live site](https://slashformotion.github.io/helix-themes-chooser/)**

## About

This project generates screenshot previews of Helix themes rendered with various programming languages, helping you choose the perfect theme for your development workflow.

## Usage

### Prerequisites

- [Nix](https://nixos.org/) with flakes enabled
- [direnv](https://direnv.net/) (optional, for automatic shell switching)

### Development

```bash
# Enter the development shell
nix develop

# Build everything
make all
```

### Output

- `public/` - Generated theme screenshots organized by theme name
- `out/` - Additional output artifacts

## Project Structure

```
.
├── flake.nix              # Nix flake for development environment
├── config.toml            # Configuration file
├── internal/              # Go internal packages
├── image-builder/         # Image generation logic
├── website-builder/       # Website generation logic
├── ressources/            # Code snippets per language
└── public/                # Generated output
```

## License

MIT
