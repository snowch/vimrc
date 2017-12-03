# nvim config

```

CONFIG_DIR=~/.config/nvim/

git clone git@github.com:snowch/vimrc.git $CONFIG_DIR

[[ -f $CONFIG_DIR/init.vim ]] && mv $CONFIG_DIR/init.vim $CONFIG_DIR/init.vim_$(date +%s)

git clone https://github.com/VundleVim/Vundle.vim.git $CONFIG_DIR/bundle/Vundle.vim

vim +PluginInstall +qall
```
