# fish-wakatime

![GitHub](https://img.shields.io/github/license/kama-meshi/fish-wakatime)

[fish](https://fishshell.com/) plugin for [WakaTime](https://wakatime.com/)  
Time tracking for commands in fish shell.

## Features

- **Automatic time tracking**
- **Project detection**
  - Git root directory name, or `Terminal`

## Getting Started

### Prerequisites

- [wakatime-cli](https://github.com/wakatime/wakatime-cli)
- [fisher 4.x](https://github.com/jorgebucaran/fisher) (optional)

### Installation

Use the command below to install, then starts to track your fish activities. Happy coding!! :sparkles:

#### fisher

```fish
pip install wakatime
fisher install kama-meshi/fish-wakatime
```

#### Manual

```fish
pip install wakatime
curl -L -o $HOME/.config/fish/conf.d/wakatime_fish_prompt.fish https://raw.githubusercontent.com/kama-meshi/fish-wakatime/main/conf.d/wakatime_fish_prompt.fish
exec fish
```

## Contribution

Pleese see [CONTRIBUTION.md](CONTRIBUTING.md).

## Licence

MIT. See [License](LICENSE) for more detail.
