# vim-config
My personal vim config.

#### General Vim commands

* Undo = u
* Redo = [control-r]
* Page up & page down = [control-f] & [control-b]
* Replace word = cw
* Switch buffers = [control-tab] go backwards by adding shift
* Close buffer = :bd
* Next/Prev buffer = :bn :bp
* List buffer = :ls
* Start new file = :e newfile.txt
* Wrap line = put cursor in line, type yss then what you want to wrap... could be HTML
* Insert new line = o or O for line before
* Delete line = dd
* Delete until end of line = D
* Join next line with current line = J
* Go to line = line# gg
* Go to end of line = $
* Go to beginning of line = 0
* turn off auto indent = set noautoindent
* see buffer commands = :b[tab]
* copy line into register = "[letter]yy (More on how to use registers)
* see all registers = :reg
* system clipboard = "*
* Vertical select = control+v then select your column, I to insert, d to delete, r to replace
* Window commands = control+w s split window, control+w hjkl move windows control+w c close window, control+q to quit a window
* Replace to end of line = c$
* Indent line = :>>
* Repeat last command = .
* find = :/[text here]
* Find next = n (previous = N)
* Find and replace = %s/searchterm/replacementtext/c (% = whole file, c = confirm change), more info
* Clear search highlight = :noh
* Text search in project = :vimgrep /regex/gj */ (then use :cw to see a list of results, more info)
* Word complete = [control-n]
* Change case = gu (lowercase), gU (uppercase)
* Recording keystrokes = q[buffer key], stop recording with q, play recording with @[buffer key]
* Help for command = :help COMMAND
* List of commands = :command optional command
* Run shell command from Vim = :![shell command]
* Close quickfix window = :ccl
h/t @christLTD
