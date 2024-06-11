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
| zf | define fold up to motion |
| zd | delete fold under cursor |
| za | toggle fold under cursor |
| zo | open fold under cursor |
| zc | close fold under cursor |
| zr | reduce all folds by one |
| zm | fold all folds by one |
| zi | toggle folding |
| ]c | jump to next change |
| [c | jump to past change |
| do / :diffg[et] | get difference |
| dp / :diffpu[t] | put difference |
| :diffthis | add current to diff |
| :dif[fupdate] | update differences |
| :diffo[ff] | exit diff mode |

### CUT & PASTE
| KEY(S) | ACTION |
| ------ | ------ |
| yy | yank line |
| 2yy | yank two lines |
| yw | yank word from cursor |
| yiw | yank word |
| yaw | yank word and space |
| y$ / Y | yank to end of line |
| p | past clipboard after |
| P | paste clipboard before |
| gp | paste back cursor forth |
| gP | paste back cursor forth |
| dd | cut line |
| 2dd | cut two lines |
| dw | cut to start of next word |
| diw | cut word |
| daw | cut word with space |
| d$ / D | cut to end of line |
| x | cut character |

### INDENT TEXT
| KEY(S) | ACTION |
| ------ | ------ |
| >> | indent one shiftwidth |
| << | de-indent one shiftwidth |
| >% | indent block with (), {} |
| >ib | indent inner block with () |
| >at | indent block with <> |
| 3== | re-indent three lines |
| =% | re-indent block with (), {} |
| =iB | re-indent inner block with () or {} |
| gg=G | re-indent entire buffer |
| ]p | paste with indent |

### SEARCH & REPLACE
| KEY(S) | ACTION |
| ------ | ------ | 
| /pattern | search for pattern |
| ?pattern | search back for pattern |
| \vpattern | 'very magic' pattern |
| n | next search result |
| N | past search result |
| :%s/old/new/g | replace all old with new |
| :%s/old/new/gc | replace all old with new with confirmations |
| :noh[lsearch] | remove search highlight |

### SEARCH MULTIPLE FILES
| KEY(S) | ACTION |
| ------ | ------ |
| :vim[grep] /pattern/ {'{file}'} | search for pattern in multiple files |
| :cn[ext] | jump to next match |
| :cp[revious] | jump to past match |
| :cope[n] | open list of matches |
| :ccl[ose] | close quickfix window |

### GLOBAL
| KEY(S) | ACTION |
| ------ | ------ |
| :h[elp] keyword | open help for keyword |
| :sav[eas] file | save file as |
| :cl[ose] | close current pane |
| :ter[minal] | open a terminal window |
| K | open man page for word under cursor |

### MACROS
| KEY(S) | ACTION |
| ------ | ------ |
| qa | record macro a |
| q | stop recording macro |
| @a | run macro a |
| @@ | rerun last run macro |

### TABS
| KEY(S) | ACTION |
| ------ | ------ |
| :tabnew | open new tab |
| C-wT | move split to tab |
| gt / :tabn[ext] | move to next tab |
| gt / :tabp[revious] | move to past tab |
| #gt | move to tab # |
| :tabm[ove] # | move tab to # |
| :tabc[lose] | close tab |
| :tabo[nly] | close all other tabs |
| :tabdo command | run command on all tabs |

### EXITING
| KEY(S) | ACTION |
| ------ | ------ |
| :w | write file |
| :w !sudo tee % | write file using sudo  |
| :wq / :x / ZZ | write and quit |
| :q | quit |
| :q! / ZQ | force quit  |
| :wqa | write and quit all tabs |

<br />

Sources: <br />
[1 (VimDeskPad.png)](https://www.reddit.com/r/linux/comments/1cqdwm2/i_dont_think_i_ever_shared_my_vim_cheatsheet_desk/) <br />
[2 (VIQuickReference.pdf)](https://www.mpaoli.net/~michael/unix/vi/summary.pdf) <br />