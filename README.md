# snip-emoji
### Usage
Enter an emoji in text form `:thumbs_up:` press tab to accept the snip and transform the text to 👍.
The full list of supported emojis can be found [here](https://github.com/carpedm20/emoji/blob/master/emoji/unicode_codes.py)

### Installation
#### vim-plug

```vim
...
Plug 'SirVer/ultisnips'
Plug 'phoffmeister/snip-emoji', { 'do': ':execute \"!\" . g:python3_host_prog . \" -m pip install emoji\" ' }
...
```

### Requirements
snip-emoji requires [ultisnips](https://github.com/SirVer/ultisnips) and `g:python3_host_prog` needs to be set to the python env for vim.
