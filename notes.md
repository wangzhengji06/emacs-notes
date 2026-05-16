Commands to remember

emacslient -c Start the emacs in gui mode

emacs -nw Start the emacs in terminal mode

# Essiential Command

C-x C-f find the file

C-x C-c quit the emacs

C-x C-s save the buffer

C-x C-b list all buffers

C-x b Switch to buffer

C-x k Kill a buffer

Esc Esc Esc take me back

C-g Bail me out

C-/ Undo

C-u <digit> Universal Argument

C-<1-9> Same as above

C-- Minus argument

# Help Command

C-h C-q Display the help

C-h i Open the info manual

C-h a Apropos to search Commands

C-h m Describe major mode

C-h x Describe the interactive command

C-h k Describe the keybind

## Info manual Command

[ ] Previous and next node

n p Move with the sibling node

l r Call out the history movement

u Go up to the parent node

q quite the info manual

# Movement Command

## Windows Management

C-x 0 Close this window

C-x 1 Close all other windows

C-x 2 Split window below

C-x 3 Split window right

C-x o Swith to other window

C-x 4 C-f Finds a file in other window

C-x 4 d Opens M-x dired in the other window

C-x 4 C-o Displays a buffer in other window

C-x 4 b Displays a buffer in other window and activate it

C-x 4 0 Kills the buffer and window

C-x 4 p Run project command in other window

## Frame Management

C-x 5 2 Create a new frame

C-x 5 0 Delete active frame

C-x 5 1 Delete other frames

C-x 5 b Switch buffer in other frame

C-x 5 C-f Finds a file in other frame

C-x 5 p Run project command in the other frame

C-x 5 d Opens M-x dired in other frame

C-x 5 C-o Displays a buffer in other frame

## Tab Bars and Tab Lines

### Tab Bar

M-x tab-bar-mode This will start the tab bar mode

C-x t 2 Creates a new tab

C-x t 0 Close the current tab

C-x t r Rename the tab

C-x t 1 Close all other tabs

C-s t b Switch buffer in other tab

C-x t d Opens M-x dired in other tab

C-x t o Next tab

C-S-<tab> Previous tab

C-x t m Move tab one position to the right

M-x tab-list Shows an interative tab list

M-x tab-undo Undoes a closed tab for each invocation

M-x tab-recent Switch to the last visited tab

M-x customize-option tab-bar-history-mode Turn on the tab bar history mode to let you go back to previous window configuration (tab)

M-[ go back to tab history

M-] go forward to tab history

### Tab Line

M-x global-tab-line-mode Turn on the global tab line mode

C-x <left> Select previous buffer

C-x <right> Select next buffer

## Elemental Movement

C-f Move forward by character

C-b Move backward by character

C-p Move to previous line

C-n Move to next line

## Move By Line

C-a Moves to beginning of line

C-e Moves to end of line

M-m Move to the first non-whitespace character on this line

## Move By Word

M-f Move forward by word

M-b Move backward by word

M-x subword-mode Minor mode that trets CamelCase as distinct workds

M-x superword-mode Minor mode that treats snake_cas as one word
