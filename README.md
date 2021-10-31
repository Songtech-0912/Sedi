# Sedi

Sedi is designed to bring the GNU Nano experience to users more familiar with a GUI. It is a simplistic text editor that follows the Unix philosophy, with a minimalist UI.

It creates new files, opens files, edits files, and saves files, that's about it (for now). More features coming.

## Current Features

- 2 modes - a code mode and prose mode
  - In code mode, which is default, the file is displayed with linenumbers using the MonoLisa font
  - In prose mode, the file is displayed without linenumbers, line spacing is increased, and the Inter font is used
- App works perfectly fine when run under sudo
- File dialogs use native system dialogs
- Pretty good design

## Planned Features

- Welcome screen + blank state screen
- Indent preservation and matching
- Support for drag and drop
- Some basic syntax highlighting
- Open files with a command palette like `fman`
- Keyboard shortcuts for the basic functions (open, edit, save)
- Vim-style Ctrl + [h j k l] navigation
