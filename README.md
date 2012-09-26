Preserve

A function for preserving window/cursor postion before running
a command and the restoring it.

Example:
```
" Re-indents buffer.
nmap <silent> <Leader>g :call Preserve("normal gg=G")<CR>
" Removes all trailing whitespace in buffer.
nmap <silent> <Leader><space> :call Preserve("%s/\\s\\+$//e")<CR>
```


From: https://docwhat.org/vim-preserve-your-cursor-and-window-state/
