
# aur-easy

A simple and minimal AUR helper for Arch Linux.

## Installation

```bash
git clone https://github.com/user14923929/aur-easy
cd aur-easy
makepkg -si
```

## Usage

```bash
# Install package from AUR
aur-easy -i <git_url>

# Update system
aur-easy -u

# Remove package
aur-easy -r <package>

# Clean cache
aur-easy -c
```

## Requirements

- `git`
- `base-devel`

## License

MIT
