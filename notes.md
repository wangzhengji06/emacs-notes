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

## Move by S expression

C-M-f Move forward by s-expression, here this is like same level

C-M-b Move backward by s-expression

## Up and down by list

Here the list means the nearest balanced expression of parentheses

C-M-d move down into a list, this means it will travel into parenthesis

C-M-u move up out of a list

It can combine with the following command:

C-M-k kill-sexp

## Forward and Backward List

C-M-n moves forward to the next list

C-M-p moves backward to the previous list

** The difference here is that, List is determined by parenthsis brackets etc, while s-expression can contain string object etc

## Other Movement Commands

M-} Move forward to the end of paragraph

M-{ Move backward to the start of paragraph

M-a Move to beginning of sentence

M-e Move to end of sentence

A good customization is M-x customize-option sentence-end-double-space so that a single space does not end a sentence.

C-M-a Move to the beginning of defun

C-M-e Move to the end of defun

C-x ] Move fowards one page

C-x [ Move backwards one page

C-v Scroll down
	
M-v Scroll up

C-M-v Scroll down the other window

C-M-S-v Scroll up the other window or you can use C-M-- C-M-v

C-x < Scroll left

C-x > Scroll right

M-< Move to the beginning of the buffer

M-> Move to the end of the buffer

C-u C-<SPC> go back to the original location

## Bookmarks and Registers

Bookmarks are permanent.

C-x r m Set a bookmark

C-x r l List bookmarks

C-x r b Jump to bookmark

Registeres are temporary.

C-x r s Store region in register

C-x r i Insert content of register at the pointer.

C-u C-x r i Insert content of register after the pointer.

## Selections and Regions

