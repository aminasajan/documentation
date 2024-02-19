# VIM Editor
## Opening Vim:

Open a terminal window on your Linux system.
```
vim filename
```
Type vim followed by the name of the file you want to edit. If the file doesn't exist, Vim will create it when you save.

## Modes:

Vim has different modes: Normal mode, Insert mode, and Command-line mode.

## Switching to Insert Mode:

- Press 'i' to switch to Insert mode. This allows you to type and edit text.
- To exit Insert mode and return to Normal mode, press the Esc key.

## Saving and Exiting:

- To save changes and exit Vim, type :wq and press Enter.
- If you want to exit without saving, type :q! and press Enter.
- If you haven't made any changes and want to exit, simply type :q and press Enter.

## Navigating in Normal Mode:

- Use ctrl + the arrow keys or h, j, k, l to move around.
- h moves left, j moves down, k moves up, and l moves right.

## Basic Editing:

In Normal mode, you can use various commands to edit text:
- x: Delete the character under the cursor.
- dd: Delete the entire line.
- yy: Yank (copy) the entire line.
- p: Paste the yanked or deleted text.
- Undo changes with u and redo with Ctrl + r.
- Replace characters with r"letter" or entire lines with R"letter".

## Search and Replace:

- Search for text with / followed by the search term.
- Search and replace using :%s/old/new/g.

## Visual Mode:

- Enter Visual mode with v to select text for copying, cutting, or deleting.
- Use V for line-based selection and Ctrl + v for block-based selection.

## Multiple Files:

- Open multiple files simultaneously with vim file1 file2.
- Switch between open files with :n (next) and :prev (previous).

## Tabs:

- Open files in tabs with vim -p file1 file2.
- Navigate between tabs with :tabnext and :tabprev.

## Window Management:

- Split the window horizontally with :split and vertically with :vsplit.
- Move between windows with Ctrl + w followed by arrow keys.
- Close a window with :q while in that window.

