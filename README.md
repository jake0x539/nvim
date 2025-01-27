# Jake's nvim config

Very basic nvim config based on kickstart-modular for math note taking
## Install (Ubuntu WSL2)
Install SumatraPDF on Windows.

```
sudo add-apt-repository ppa:neovim-ppa/unstable -y
sudo apt update
sudo apt install make gcc ripgrep unzip git xclip neovim cargo
cargo install --locked tree-sitter-cli
```

Add this to your ``~/.bashrc`` (or whichever shell you're currently using) so nvim has access to tree-sitter:
```export PATH="$PATH:$HOME/.cargo/bin/"```
Also add ```:/mnt/c/[path to sumatrapdf.exe]``` to your PATH.

Clone the config:
```git clone https://github.com/jake0x539/nvim.git "${XDG_CONFIG_HOME:-$HOME/.config}"/nvim```
