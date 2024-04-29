# NvChad-python-config
Custom config of Nvim (NvChad) as a Python IDE.
Inspired from [Dreams of Code](https://github.com/dreamsofcode-io/neovim-python)

# Plugins
- Pyright - Static Type Checker
- Black - Formatter (configured on-save)
- Ruff - LSP
- MyPy - Static Type Checker
- DebugPy - Debugging

# Installation
```bash
git clone https://github.com/dobval/NvChad-python-config.git ~/.config/nvim/lua/custom
```
Then run `nvim` and let everything install.

Restart Neovim and install the treesitter syntax
```bash
:TSInstall python
```
