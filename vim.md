## Curser Movement

w              - jump by beginning of each word
b              - jump backwards by word
e              - jump by end of each word
0              - jump to start of line        
$              - jump to end of line
ctrl + d       - move down half page
ctrl + u       - move up half page
}              - jump forward by paragraph 
{              - jump backward by paragraph
gt             - go to next tab
gT             - got back one tab
gg             - goes to the top of page
G              - goes to bottom of page
linenumber + G - goes to line number
yy             - yank the entire line without needing to go to visual mode
zz             - make your current line to the center of the screen
:e.            - browse current working directory
:set number    - show line numbers
:set no number - hide line numbers (for copy pasting)

## Screen Management

ctrl + ^                   - back to previous edit point
:ls                        - list all open buffers
:b<number>                 - switch to a specific buffer
:bp                        - buffer previous
:vsp                       - vertical split
:sp                        - horizontal split
ctl + w (h or j or k or l) - move around to different splits
ctrl + w |                 - full screen your current split
:bd                        - buffer delete
:pwd                       - print out current working directory

## Visual Mode

v             - visual mode by character
V             - visual mode by line
ctrl + v      - block visual mode
shift + i     - do this in block mode to make bulk edit, then hit escape 
                to apply the change to all selected lines

vi<character> - select everything between <character>

## Search and Replace

*                    - highlight all instances of variable you're on
, v                  - remove highlight
:%s/search/replace/g - search and replace in entire file 
/searchterm          - search for searchterm
n                    - jump to next instance of searchterm
N                    - jump to previous instance of searchterm

## Insert Mode

A    - insert mode at the end of the line
cc   - change (replace) an entire line

## CtrlP

ctrl + p - normal menu
ctrl + e - recent file search
ctrl + r - tag search

once CtrlP is open
ctrl + (j or k) - scroll
ctrl + t        - open file in new tab
ctrl + y        - create new file and its parent directories

## Vinegar

- - open up the e. file browser
- (when it's already open) - to go up a level
d - create a directory
D - delete the directory or file
% - new file
