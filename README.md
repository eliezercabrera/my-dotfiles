Use the `stow` command, e.g.

    stow nvim
    stow tmux
    ...

to create symlinks at the appropriate locations to this repository's files.

Vundle requires extra instructions. Run

    git clone https://github.com/VundleVim/Vundle.vim.git

inside `Vundle.vim`

Then, launch `nvim` and run

    :PluginInstall
