# This contains my learning of vim

- show the line numbers by typing
```bash
:set nu
```

- To copy files content to another file. Use visual mode to select the content then then use below
```bash
:'<,'>w newfile # copy the selected content to newfile
``` 

-  To shift lines by x char from the begining of line. [stackoverflow](https://stackoverflow.com/questions/7592314/how-to-insert-a-block-of-white-spaces-starting-at-the-cursor-position-in-vi
)
```bash
<S-v> to enter VISUAL-LINE mode
3j or jjj or /D<CR> to select the lines
:norm I<Space><Space>, the correct range ('<,'>) being inserted automatically
```
