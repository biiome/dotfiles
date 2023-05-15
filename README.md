# Dotfiles
This is where my dotfiles live.

## How to use:
1. Install chezmoi 
    `sh -c "$(curl -fsLS get.chezmoi.io)" -- -b $HOME/.local/bin`
2. Initialise chezmoi with this repo:
    `chezmoi init https://github.com/biiiome/dotfiles.git`
3. Check what changes chezmoi will make to your home directory by running:
    `chezmoi diff`
4. If you are happy with the changes will make then run:
    `chezmoi apply -v`
5. On any machine, you can pull and apply the latest changes from your repo with:
    `chezmoi update -v` 
