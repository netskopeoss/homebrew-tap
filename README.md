# Netskope Homebrew Tap

Official [Homebrew](https://brew.sh/) tap for [Netskope CLI](https://github.com/netskopeoss/netskope-cli) tools.

## Installation

```bash
brew tap netskopeoss/tap
brew install netskope
```

## Upgrade

```bash
brew update
brew upgrade netskope
```

## Usage

```bash
# Full command name
netskope --help

# Short alias
ntsk --help

# Quick setup
netskope config set-tenant mytenant.goskope.com
netskope config set-token
netskope alerts list --limit 5
```

## Alternative Installation Methods

```bash
# pipx (recommended for isolated install)
pipx install netskope

# pip
pip install netskope
```

## More Information

- [Netskope CLI Documentation](https://github.com/netskopeoss/netskope-cli)
- [PyPI Package](https://pypi.org/project/netskope/)
