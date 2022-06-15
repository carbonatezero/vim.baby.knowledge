# vim: the absolute basics
Daily used commands of vim


### Existing

`:q`  
`:q!`  
`:w`  
`:wq`  


### Cursor movement

---
`h` `j` `k` `l` | Arrow keys  
`ctrl+f/b` | forward/backward  
`ctrl+d/u` | move down/up half page  
`G`        | go to the bottom of the page  
`gg`       | go to the top of the page  
`{`        | forward one paragraph  
`}`        | backward one paragraph  
`ctrl+e\y` | scroll down/up one line  

`0`        | start of line  
`^`        | start of line after white space  
`$`        | end of line  
`%`        | jump between matching () or {}  


---

### Editting

`u`      | Undo  
`ctrl+r` | Redo  
`i`/`a`  | Start insert mode at/after cursor  
`I`/`A`  | Start insert mode at the beginning/end of the line

### Visual mode (slecting text)

### Clipboard

`y` | copy the selcted characters in the visual mode  
`p` | paste after cursor

### Search/Replace

`:%s/<old>/<new>/g` | replace all <old> with <new> throughout file  
`:%s/<old>/<new>/gc` | replace all <old> with <new> throughout file with confirmation  

`/<text>` search for <text>  
`?<text>` search for <text> backward  
  









[To be added.]
