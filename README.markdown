* exec a file: :!bash %   ( :! % should work according to IRC but doesn't?)

* map <D-r> :!%<CR>

* help for executing files
        :help :!
        :help :range!

* set font
        :set guifont=*
        :set guifont?
        :set guifont=Monaco:h21  (put in .gvimrc)

* NERD tree
        :edit ~/
        :tabedit ~/
        Shift-A - zoom
        Shift-R - refresh root node
        :NERDTree - reopen nerdtree
        m - from nerdtree presents filesystem menu

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

* Highlighting lines and indenting
        vjjj>   - visual mode, highlight 3 lines, indent
        v20G>    - visual mode, go to line 20, indent

* view hex
        :%!xxd

* Ack
        cmd-shift-F
        --all to search all files


scratch
foo
bar
baz
