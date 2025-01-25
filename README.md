# VIM Editor Commonly Used Commands

## Table of Contents
1. [Introduction](#introduction)
2. [Basic Navigation](#basic-navigation)
3. [Editing Text](#editing-text)
4. [Editing Text Clipboard Access](#editing-text-clipboard-access)
5. [Saving and Exiting](#saving-and-exiting)
6. [Search and Replace](#search-and-replace)
7. [Visual Mode](#visual-mode)
8. [Miscellaneous Commands](#miscellaneous-commands)
9. [Comment and Uncomment](#comment-and-uncomment)

## Introduction
VIM is a highly configurable text editor built to enable efficient text editing. This guide covers some of the most commonly used commands in VIM.

## Basic Navigation
- `h` - Move cursor left
- `j` - Move cursor down
- `k` - Move cursor up
- `l` - Move cursor right
- `w` - Move to the beginning of the next word
- `b` - Move to the beginning of the previous word
- `0` - Move to the beginning of the line
- `$` - Move to the end of the line

## Editing Text
- `i` - Insert mode before the cursor
- `a` - Insert mode after the cursor
- `o` - Open a new line below the current line and enter insert mode
- `x` - Delete the character under the cursor
- `dd` - Delete the current line
- `yy` - Yank (copy) the current line
- `p` - Paste the yanked or deleted text after the cursor

## Editing Text Clipboard Access
- `"*dd` - cut a line (or 3dd to cut three lines)
- `"*yy` - copy a line (or 3yy to copy three lines)
- `"*p` - paste line(s) on line after the cursor
- `"*P` - paste line(s) on line before the cursor


## Saving and Exiting
- `:w` - Save the current file
- `:q` - Quit VIM
- `:wq` - Save and quit
- `:q!` - Quit without saving

## Search and Replace
- `/pattern` - Search for `pattern`
- `n` - Move to the next occurrence of the search pattern
- `N` - Move to the previous occurrence of the search pattern
- `:%s/old/new/g` - Replace all occurrences of `old` with `new` in the file

## Visual Mode
- `v` - Enter visual mode (character-wise selection)
- `V` - Enter visual line mode (line-wise selection)
- `Ctrl+v` - Enter visual block mode (block-wise selection)
- `y` - Yank (copy) the selected text
- `d` - Delete the selected text

## Miscellaneous Commands
- `u` - Undo the last change
- `Ctrl+r` - Redo the last undone change
- `.` - Repeat the last command
- `:%!command` - Filter the entire file through an external command

## Comment and Uncomment
### Comment
- `ctrl+v` - Enter visual mode
- `↑/↓` - Select lines to comment
- `shift+i` - Press capital I
- `//` - Insert the comment text, e.g. #
- `esc esc` - Press ESC two times

### Uncomment
- `ctrl+v` - Enter visual mode
- `↑/↓` - Use this to select lines to uncomment
- `shift + ←/→` - Use this to select multiple characters
- `d or x` - Press to delete the characters

This guide provides a quick reference to some of the most commonly used VIM commands. For more detailed information, refer to the VIM documentation.
