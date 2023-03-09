# vim: the cheat sheet
Daily used commands of vim


### Existing

`:q`  `:q!`  `:w`  `:wq`  


### Cursor movement

Command | Description
--- | ---
`h` `j` `k` `l` | Arrow keys
`Ctrl+f/b` | Forward/backward
`Ctrl+d/u` | Move down/up half page
`G` | Go to the bottom of the page
`gg` | Go to the top of the page
`{` | Forward one paragraph
`}` | Backward one paragraph
`Ctrl+e/y` | Scroll down/up one line
`0` | Start of line
`^` | Start of line after white space
`$` | End of line
`%` | Jump between matching () or {}


---

### Editting

`u`      : Undo  
`ctrl+r` : Redo  
`i`/`a`  : Start insert mode at/after cursor  
`I`/`A`  : Start insert mode at the beginning/end of the line

### Visual mode (slecting text)
`v`  
`V`  
`ctrl+v`  


### Clipboard

`y` : copy the selcted characters in the visual mode  
`p` : paste after cursor

### Search/Replace

`:%s/<old>/<new>/g` : replace all <old> with <new> throughout file  
`:%s/<old>/<new>/gc` : replace all <old> with <new> throughout file with confirmation  

`/<text>` search for <text>  
`?<text>` search for <text> backward  
  
### To comment out blocks in vim: 

- press <kbd>Esc</kbd> (to leave editing or other mode)
- hit <kbd>ctrl</kbd>+<kbd>v</kbd> (visual block mode)
- use the <kbd>j</kbd>/<kbd>k</kbd> "arrow keys" to select lines you want (it won't highlight everything - it's OK!)
- <kbd>Shift</kbd>+<kbd>i</kbd> (capital I)
- insert the text you want, e.g. `% `
- press <kbd>Esc</kbd><kbd>Esc</kbd>

---
  
No need to go beyond the commands above. 
