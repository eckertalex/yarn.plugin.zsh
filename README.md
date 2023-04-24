# yarn.plugin.zsh

> A yarn aliases plugin for zsh

## Installation

### Znap

I recommend using [Znap](https://github.com/marlonrichert/zsh-snap) or installing the plugin manually. You can also install it using any 3rd-party framework or plugin manager you like, but I won't document that here.

Just add this to your .zshrc file:

`znap source eckertalex/yarn.plugin.zsh`

To update, run `znap pull`.

### Oh My Zsh

1. Clone the repository:

   `git clone --depth=1 https://github.com/eckertalex/yarn.plugin.zsh.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/plugins/yarn`

2. Include it in your `~/.zshrc`

   `plugins=(... yarn)`

## Aliases

### General

| Alias | Command |
| ----- | ------- |
| `y`   | `yarn`  |

### Dependency Management

| Alias  | Command          |
| ------ | ---------------- |
| `yi`   | `yarn install`   |
| `yl`   | `yarn list`      |
| `yout` | `yarn outdated`  |
| `ya`   | `yarn add`       |
| `yad`  | `yarn add --dev` |
| `yrm`  | `yarn remove`    |

### Development

| Alias | Command      |
| ----- | ------------ |
| `yst` | `yarn start` |
| `yd`  | `yarn dev`   |
| `yb`  | `yarn build` |
| `ylt` | `yarn lint`  |

### Testing

| Alias | Command                |
| ----- | ---------------------- |
| `yt`  | `yarn test`            |
| `ytc` | `yarn test --coverage` |

## Changelog

### 2023-04-24

- Initial commit
