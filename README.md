# Nik's AstroNvim Template

Most of AstroNvim is stock including the leader key `space`

I have a few pre-installed packages with custom commands:

Markdown Preview (opens a MarkDown preview of the current file in the browser).

You may need to run this command if it doesn't work!
```
:call mkdp#util#install()
```

and some minor fixes for working with clangd.

**NOTE:** This is for AstroNvim v4+

A template for getting started with [AstroNvim](https://github.com/AstroNvim/AstroNvim)

## 🛠️ Installation

##### Install Nerd fonts 

Here is the one I use:

https://github.com/ryanoasis/nerd-fonts/releases/download/v3.2.1/0xProto.zip

```
mkdir -p ~/.fonts
cp ~/Downloads/0xProto.zip ~/.fonts
cd ~/.fonts
unzip 0xProto.zip && rm 0xProto.zip
fc-cache -fv
```

#### Install NeoVim
```
sudo snap install nvim --classic
```

#### Make a backup of your current nvim and shared folder (Optional)

```shell
mv ~/.config/nvim ~/.config/nvim.bak
mv ~/.local/share/nvim ~/.local/share/nvim.bak
mv ~/.local/state/nvim ~/.local/state/nvim.bak
mv ~/.cache/nvim ~/.cache/nvim.bak
```

#### Create a new user repository from this template (Optional)

Press the "Use this template" button above to create a new repository to store your user configuration.

You can also just clone this repository directly if you do not want to track your user configuration in GitHub.

#### Clone the repository

```shell
git clone https://github.com/<your_user>/<your_repository> ~/.config/nvim
```

#### Start Neovim

```shell
nvim
```
