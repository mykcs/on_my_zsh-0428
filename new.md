# Path to your oh-my-zsh installation.
export ZSH="$HOME/.oh-my-zsh"

# Set name of the theme to load --- if set to "random", it will
# load a random theme each time oh-my-zsh is loaded, in which case,
# to know which specific one was loaded, run: echo $RANDOM_THEME   
# See https://github.com/robbyrussell/oh-my-zsh/wiki/Themes
ZSH_THEME="robbyrussell"

plugins=(
    git
    zsh-autosuggestions
    zsh-syntax-highlighting
)

source $ZSH/oh-my-zsh.sh

# ---- [myk] ----

# >>> conda initialize >>>
# !! Contents within this block are managed by 'conda init' !!
__conda_setup="$('/Users/myk/anaconda3/bin/conda' 'shell.zsh' 'hook' 2> /dev/nu$
if [ $? -eq 0 ]; then
    eval "$__conda_setup"
else
    if [ -f "/Users/myk/anaconda3/etc/profile.d/conda.sh" ]; then
        . "/Users/myk/anaconda3/etc/profile.d/conda.sh"
    else
        export PATH="/Users/myk/anaconda3/bin:$PATH"
    fi
fi
unset __conda_setup
# <<< conda initialize <<<
