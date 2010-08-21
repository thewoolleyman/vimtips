* exec a file: :!bash %   ( :! % should work according to IRC but doesn't?)

* map <D-r> :!%<CR>

* help for executing files
        :help :!
        :help :range!

* set font
        :set guifont=*
        :set guifont?
        :set guifont=Monaco:h21

* NERD tree
        :edit ~/
        :tabedit ~/
        Shift-A - zoom
        Shift-R - refresh root node

* split
        :split
        CTRL-W arrow key to switch windows

* Change files
        ctrl-i, ctrl-o - cursor history location
        ctrl-^ - toggle last file locations
            
* buffers
        :buffers
        :b<n>
        :bn, :bN (next previous, maybe map to cmd-option-rightleft)
        :bd - delete current buffer from buffer list
