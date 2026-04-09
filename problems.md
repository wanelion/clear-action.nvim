<!-- markdownlint-disable MD033 -->
# Note for `wanelion/virt-notes.nvim`

## Thoughts

All thoughts implemented

## To-do

- Implement 'open-float' for extmarks
-- Get and improve from 'clear-action'
- Create telescope extension

## Bugs

No bugs for now

## Not planned

- Add amount notes number to `lualine`
- Place note after Language Server Protocol (LSP) errors
- Put 'clear-action' numbers before note
- Make human-readable note format in text file
- Add key map go to note file

## Impossible in current implementation

- Test manually inserted files (add option to use `BufEnter` instead of `BufRead`)
- Redraw all notes at the current line for visual clarity
- Remove underlinings from trailing whitespaces

## Valuable notes from complete

- Notes might be too close to actual text; consider better color or symbol (for
example, "<")

simple note<br>
.also simple note<br>
-suggestion note<br>
?warning note<br>
!error note<br>

<p style="color: #6bffff">< simple note</p>
<p style="color: #6bffff">< also simple note</p>
<p style="color: #4db6ac">< suggestion note</p>
<p style="color: #42a5f5">< warning note</p>
<p style="color: #ff9800">< error note</p>

-- change to table `schemas.warn.label|ns_hl|ns_text|color`
