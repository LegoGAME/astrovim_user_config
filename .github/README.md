# AstroNvim User Configuration

Шаблон для [AstroNvim](https://github.com/AstroNvim/AstroNvim)

## 🛠️ Installation

#### Make a backup of your current nvim and shared folder

```shell
mv ~/.config/nvim ~/.config/nvim.bak
mv ~/.local/share/nvim ~/.local/share/nvim.bak
```

#### Clone AstroNvim Unix

```shell
git clone https://github.com/AstroNvim/AstroNvim ~/.config/nvim
```

#### Clone AstroNvim Windows

```shell
git clone https://github.com/AstroNvim/AstroNvim $env:LOCALAPPDATA\nvim
```

#### Clone the repository Unix

```shell
git clone https://github.com/LegoGAME/astrovim_user_config ~/.config/nvim/lua/user
```

#### Clone the repository Windows

```shell
git clone https://github.com/LegoGAME/astrovim_user_config $env:LOCALAPPDATA\nvim\lua\user
```

#### Start Neovim

```shell
nvim
```

#### Remove config
```shelll
rm -rf ~/.config/nvim/ && rm -rf ~/.cache/nvim && rm -rf ~/.local/share/nvim && rm -rf ~/.local/state/nvim
```
