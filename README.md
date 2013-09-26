# pastek.vim

`pastek.vim` is a Vim syntax file for [Pastek][pastek] files.

[pastek]: https://github.com/pastek-project/pastek_core

## Install

[Download][vim-scripts] the latest version of the file, and drop it into your
`~/.vim/syntax/` directory:

```sh
mkdir -p ~/.vim/syntax
wget http://www.vim.org/scripts/download_script.php?src_id=20850 \
    -O ~/.vim/syntax/pastek.vim
```

Then add the following line to your `~/.vimrc` file:

```vim
au BufNewFile,BufRead *.pastek set ft=pastek
```

[vim-scripts]: http://www.vim.org/scripts/script.php?script_id=4730
