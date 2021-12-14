# Features
- NerdTree filesystem: Ctrl+n to open/close
- Intergrated terminal: Alt+t to open(close is simply :q or type exit on terminal)
- Coc-c++ intellisense: Remember to set CMake configuration
  ```cmake
  set(CMAKE_EXPORT_COMPILE_COMMANDS ON)
  ```
  Please open terminal and type 
  ```bash
  ln -s build/compile_commands.json .
  ```
  After that, you'll have the correct c++ intellisense in vim.
- CMake build: Ctrl+b to build, Ctrl+c to close the window.
- Some themes: best for me, please enjoy by yourselves.
# Installation
## Install neovim
```bash
sudo apt-get install neovim
```
## Install vim-plug
```bash
sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
```
## Install plugins
Open vim, type :PlugInstall. And all required plugins will be installed.

## Install coc.nvim plugins
```vim
:CocInstall coc-clangd coc-cmake coc-highlight coc-markdown-preview-enhanced coc-markdownlint coc-pairs coc-pyright coc-sh coc-snippets coc-syntax coc-vimlsp coc-webview coc-yaml
```

## Unfinished works
coc-snippets is not set effectively, fuzzy search is still unkown for me.

# Enjoy it!
