**Note:** <br />
C- = *Ctrl +* <br />
A- = *Alt +* <br />
M- = *Meta +* <br />

### INSERT MODE
| KEY(S) | ACTION |
| ------ | ------ |
| i | insert before cursor |
| I | insert before line |
| a | append after cursor |
| A | append after line |
| o | append new line below |
| O | append new line above |
| ea | insert after word |
| C-h | delete before cursor |
| C-w | delete word before cursor |
| C-j | begin new line |
| C-t | indent line to right |
| C-d | de-indent line to left |
| C-n | insert next match |
| C-p | insert previous match |
| C-rx | insert register x |
| C-ox | normal mode command |
| Esc | exit insert mode |

### EDITING
| KEY(S) | ACTION |
| ------ | ------ |
| r | replace character |
| R | replace until Esc |
| J | join line below |
| gJ | join line below no space |
| gwip | reflow paragraph |
| g~ | switch casing |
| gu | change to lowercase |
| gU | change to uppercase |
| cc | replace entire line |
| c$ / C | replace to end of line
| ciw | replace entire word |
| cw / ce | replace to end of word |
| s | substitute with text |
| S | substitute line with text |
| xp | transpose two letters |
| u | undo |
| U | under last changed line |
| C-r | redo |
| . | repeat last command |

### CURSOR MOVEMENT
| KEY(S) | ACTION |
| ------ | ------ |
| h | move cursor left |
| j | move cursor down |
| k | move cursor up |
| l | move cursor right |
| gj | move cursor down+ |
| gk | move cursor up+ |
| H | move to top |
| M | move to middle |
| L | move to bottom |
| w | jump to start of word |
| W | jump to start of word+ |
| e | jump to end of word |
| E | jump to end of word+ |
| b | fall to start of word |
| B | fall to start of word+ |
| ge | fall to end of word |
| gE | fall to end of word+ |
| % | move to matchpair |
| 0 | jump to start of line |
| ^ | jump to first character |
| $ | jump to end of life |
| g_ | jump to last character |
| gg | jump to first line |
| G | jump to last line |
| 5gg / 5G | jump to line 5 |
| gd | jump to local declaration |
| gD | jump to global declaration |
| fx | jump to next x |
| tx | jump to before next x |
| Fx | jump to previous x |
| Tx | jump to after previous x |
| ; | repeat last jump |
| , | repeat last jump back |
| } | jump to next paragraph |
| { | jump to last paragraph |
| zz | center cursor |
| C-e | move screen down |
| C-y | move screen up |
| C-b | move back full screen |
| C-f | move ahead full screen |
| C-d | move ahead half screen |
| C-u | move back half screen |

### MULTIPLE FILES
| KEY(S) | ACTION |
| ------ | ------ |
| :e[edit] file | edit a file |
| :bn[ext] | go to next buffer |
| :bp[revious] | go to previous buffer |
| :bd[elete] | delete a buffer |
| :b[uffer]# | go to buffer by index |
| :ls / :buffers | go to buffer by file |
| :sp[lit] file | open file in split view |
| :vs[plit] file | open file in split view |
| :vert[ical] ba[ll] | edit all buffers in split |
| :tab ba[ll] | edit all buffers as tabs |
| C-ws | split window |
| C-wv | split window vertically |
| C-ww | switch windows |
| C-wq | quit a window |
| C-wx | switch window with next |
| C-w= | equalize all windows |
| C-wh | move cursor to left |
| C-wl | move cursor to right |
| C-wj | move cursor down |
| C-wk | move cursour up |
| C-wH | full height window left |
| C-wL | full height window right |
| C-wJ | full width window down |
| C-wK | full width window top |

### MARKING
| KEY(S) | ACTION |
| ------ | ------ |
| v | visual mode |
| V | linewise visual mode |
| o | move to end of marked |
| C-v | visual block mode |
| O | move to other corner |
| aw | mark a word |
| ab | a block with () |
| aB | a block with {} |
| at | a block with <> tags |
| ib | inner block with () |
| iB | inner block with {} |
| it | inner block with <> tags |
| Esc | exit visual mode |

### VISUAL COMMANDS
| KEY(S) | ACTION |
| ------ | ------ |
| > | shift text right |
| < | shift text left |
| y | yank marked text |
| d | delete marked text |
| ~ | switch case |
| u | marked to lowercase |
| U | marked to uppercase |

### REGISTERS
| KEY(S) | ACTION |
| ------ | ------ |
| :reg[isters] | show registers content |
| "xy | yank into register x |
| "xp | paste contents of x |
| "+y | yank into sys clipboard |
| "+p | paste out sys clipboard |

### MARKS & POSITION
| KEY(S) | ACTION |
| ------ | ------ |
| :marks | list of marks |
| ma | set position for mark A |
| `a | jump to mark A |
| y`a | yank text to mark A |
| `0 | jump to last exit point |
| `" | go to last edit point |
| `. | return from last jump |
| :ju[mps] | list of jumps |
| C-i | go to next jump in list |
| C-o | go to past jump in list |
| :changes | list of changes |
| g, | go to next change in list |
| g; | go to past change in list |
| C-] | jump to tag below |

### DIFF
| KEY(S) | ACTION |
| ------ | ------ |

### CUT & PASTE
| KEY(S) | ACTION |
| ------ | ------ |

### INDENT TEXT
| KEY(S) | ACTION |
| ------ | ------ |

### SEARCH & REPLACE
| KEY(S) | ACTION |
| ------ | ------ | 

### SEARCH MULTIPLE FILES
| KEY(S) | ACTION |
| ------ | ------ |

### GLOBAL
| KEY(S) | ACTION |
| ------ | ------ |

### MACROS
| KEY(S) | ACTION |
| ------ | ------ |

### TABS
| KEY(S) | ACTION |
| ------ | ------ |

### EXITING
| KEY(S) | ACTION |
| ------ | ------ |

<br />

Sources: <br />
[1 (VimDeskPad.png)](https://www.reddit.com/r/linux/comments/1cqdwm2/i_dont_think_i_ever_shared_my_vim_cheatsheet_desk/) <br />
[2 (VIQuickReference.pdf)](https://www.mpaoli.net/~michael/unix/vi/summary.pdf) <br />