# Emacs Tutorial Summary

|Command|Description|
|---|---|
|`C-x C-c`|Quit Emacs (end current session)|
|`C-g`|Quit a partially entered command|
|`C-u #` or `M-#`|Prefix argument; repeat command|
|`C-/` or `C-_` or `C-u x`|Undo previous command|

### Page movement

|Command|Description|
|---|---|
|`C-v`|Move forwards one screen|
|`M-# C-v`|Scroll forwards `#` lines|
|`M-v`|Move backwards one screen|
|`M-# M-v`|Scroll backwards `#` lines|
|`C-l`|Clear screen and redisplay all text, moving the text around the cursor and the cursor itself, to the centre of the screen|
|`C-l C-l`|Move current line to top of screen|
|`M-<`|Move to start of document|
|`M->`|Move to end of document|

### Cursor Control

|Command|Description|
|---|---|
|`C-p`|↑ Previous line|
|`C-n`|↓ Next line|
|`C-b`|← Backward one character|
|`C-f`|→ Forward one character|
|`M-# C-{pnbf}`|Move cursor `#` times in corresponding direction|
|`M-f`|Forward one word|
|`M-b`|Backward one word
|`C-a`|Move to beginning of line|
|`C-e`|Move to end of line
|`M-a`|Move to beginning of current sentence|
|`M-e`|Move to end of current sentence|

### Deleting, Killing, Yanking

- **Kill**: Delete text that can be reinserted later
- **Yank**: Reinsert deleted text.

|Command|Description|
|---|---|
|`<DEL>`|"Backspace"|
|`C-d`|Delete next character after the cursor|
|`M-<DEL>`|Kill word immediately before (left of) the cursor|
|`M-d`|Kill word after (right of) the cursor|
|`C-k`|Kill from cursor position to the end|
|`M-k`|Kill to the end of the current sentence|
|`C-<SPC>`|Set mark|
|`C-w`|Kill marked region|
|`C-y`|Yank text back (reinsert killed text)|
|`M-y`|Cycle through earlier killed texts|

### Files

|Command|Description|
|---|---|
|`C-x C-f`|Find a file|
|`C-x C-s`|Save a file|
|`C-x s`|Save each file-visiting buffer to its file|
|`M-x recover-this-file`|Recover a saved auto-save file (saved as `#file#`)|

### Buffers

- **Buffers**: Files are opened in new buffers within emacs

|Command|Description|
|---|---|
|`C-x C-b`|List buffers|
|`C-x 1`|Get rid of buffer list|
|`C-x b name`|Switch to buffer `name`|

### Modes

- **Major mode**: At any given time only one major mode can be active.
- **Minor mode**: Many minor modes can be active at any time.

|Command|Description|
|---|---|
|`C-h m`|View documentation for current major mode|
|`M-x fundamental-mode`|Switch to `Fundamental` major mode|
|`M-x text-mode`|Switch to `Text` major mode|
|`M-x auto-fill-mode`|Turn on `Auto Fill` minor mode, breaking lines between words after text goes past set character limit. `C-x f` to set character line limit. `M-q` to re-fill previously edited paragraph.|


### Searching

- During a search, repeating the command (`C-s` or `C-r`) and `<DEL>` (backspac)e move the search forwards and backwards.

|Command|Description|
|---|---|
|`C-s`|Forward search|
|`C-r`|Reverse search|

### Windows

|Command|Description|
|---|---|
|`C-x 2`|Split screen into two windows|
|`C-M-v`|Scroll bottom window|
|`C-x o`|Move cursor between open windows|
|`C-x 1`|Close other windows|

### Frames

- **Frame**: A graphical window in XEmacs

|Command|Description|
|---|---|
|`C-x 5 2`|Create a new frame|
|`C-x 5 0`|Remove the selected frame|
