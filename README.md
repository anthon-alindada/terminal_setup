# Terminal (Dev) Setup
My terminal configuration and setup for development

## Screenshot
![Screenshot](terminal_screenshot.png?raw=true "Optional Title")

## Main tools used
* zsh
* tmux
* vim

## Zsh
Zsh configurations (Minimal)

#### Plugins
* [OhMyZsh](https://ohmyz.sh/): Zsh configuration manager
* [powerlevel10k](https://github.com/romkatv/powerlevel10k): Zsh theme

#### Other Notes
* Remove git status in ```~/.p10k.zsh``` to have more cleaner look in terminal
* Copy configs in ```~/.zshrc```

## Tmux
Tmux configurations, plugins, and key mappings

#### Plugins
* [tmp](https://github.com/tmux-plugins/tpm): Tmux plugin manager
* [tmux-power](https://github.com/wfxr/tmux-power): Tmux powerline theme

#### Key Mappings
The prefix is ``` ` ```

Panes navigation
* Left ```J```
* Down ```K```
* Up ```L```
* Right ```;```

Resize panes
* Resize to left by 3 ```Arrow-Left>```
* Resize to down by 3 ```<Arrow-Down>```
* Resize to up by 3 ```<Arrow-Up>```
* Resize to right by 3 ```<Arrow-Right>```

Split panes
* Split pane horizontally ```|``` or ```\```
* Split pane vertically ```-``` or ```_```

#### Other Notes
* Make sure you use version 3 or higher
* Copy configs in ```~/.tmux.conf```

## Vim
Vim configurations, plugins, and key mappings

#### Plugins
* [ack](https://github.com/mileszs/ack.vim): String search engine
* [ale](https://github.com/dense-analysis/ale): Lint engine
* [ayu-vim](https://github.com/ayu-theme/ayu-vim): Theme
* [ctrlp.vim](https://github.com/kien/ctrlp.vim): Search file
* [lightline.vim](https://github.com/itchyny/lightline.vim): Colorscheme
* [nerdcommenter](https://github.com/preservim/nerdcommenter): Code commenter
* [nerdtree](https://github.com/preservim/nerdtree): File system explorer
* [python-imports](https://github.com/mgedmin/python-imports.vim): Python fix imports
* [tagbar](https://github.com/preservim/tagbar): Tagbar
* [vim-anyfold](https://github.com/pseewald/vim-anyfold): Code fold
* [vim-devicons](https://github.com/ryanoasis/vim-devicons): Icons
* [vim-isort](https://github.com/fisadev/vim-isort): Python Isort
* [vim-pydocstring](https://github.com/heavenshell/vim-pydocstring): Python docstring
* [YouCompleteMe](https://github.com/ycm-core/YouCompleteMe): Autocomplete

#### Key Mappings
The leader is ```,```

Remap cursor navigation
* Left ```j```
* Down ```k```
* Up ```l```
* Right ```;```

Pane navigation
* Left ```Ctrl+h```
* Down ```Ctrl+j```
* Up ```Ctrl+k```
* Right ```Ctrl+l```

Autocomplete navigation
* Down ```Ctrl+j```
* Up ```Ctrl+k```

NERDTree toggle ```Ctrl+n```

New Tab ```Ctrl+t```

## Etc
* Install [Fuzzy Finder](https://github.com/junegunn/fzf)
* Install [NerdFonts](https://github.com/ryanoasis/nerd-fonts)
* Use ```MesloLGS NF Regular``` font
* Add ```export TERM=xterm-256color```
* Change terminal background to ```#1A1A1A```
* Change ayu theme colors
    * ```#1d2026``` to ```#1A1A1A```
    * ```#151A1E``` to ```#262626```
    * ```#14191F``` to ```#1E1E1E```
