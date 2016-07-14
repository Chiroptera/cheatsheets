
## General

| Command | Linux | Description |
| ------- | ----- | ----------- |
| Preferences/Settings | ctrl-, | Opens the Preferences/Settings view |
| Command Palette | ctrl-shift-p | Opens & closes the command palette |
| Open File (Fuzzy) | ctrl-p | Opens the Fuzzy Finder palette in which you can search and open files |
| Add project folder | ctrl-alt-o | Tracks folder |
| Browse Open Files | ctrl-b | Browse tabs within the window |
| Grammar Selector | ctrl-shift-l | Selects the language the file is in |
| Markdown Preview | ctrl-shift-m | Previews the file in the Markdown format |
| Key Binding Resolver | ctrl-. | Shows what key bindings the pressed key combination resolves to |
| Toggle Tree View | ctrl-k ctrl-b or ctrl-\ | Toggles Atom's file Tree View |
| Reload Atom | alt-ctrl-r | Reloads the Editor |
| Toggle Developer Tools | `ctrl-shift-i` | Opens up the Chrome Developer Tools/Console |
| Show Available Snippets | `alt-shift-s` | Shows the snippets available to Atom |

## Window Management

| Command | Linux | Description |
| ------- | ----- | ----------- |
| New File | `ctrl-n` | Opens an empty file in a new tab |
| New Window| `ctrl-shift-n` | Opens a new editor window |
| Open | `ctrl-o` | Shows the _Open File_ dialog, which lets you select a file to open in the editor |
| Open Folder | `ctrl-shift-o` | Shows the _Open Folder_ dialog, which lets you select a folder to add to the editor's Tree View |
| Save | `ctrl-s` | Saves the currently active file |
| Save As | `ctrl-shift-s` | Saves the currently active file under a different name  |
| Close Tab | `ctrl-w` | Closes the currently active tab|
| Close Window | `ctrl-shift-w` | Closes the currently active editor window  |
| Split pane down | ctrl-k down | |
| Split pane left | ctrl-k left | |
| Split pane right | ctrl-k right | |
| Split pane up | ctrl-k up | |
| Focus pane below | ctrl-k ctrl-down	| Focus on the downward pane |
| Focus pane left | ctrl-k ctrl-left	| Focus on the pane to the left |
| Focus pane right | ctrl-k ctrl-right	| Focus on the pane to the right |
| Focus pane up | ctrl-k ctrl-up	| Focus on the upward pane |
| Focus pane next | ctrl-k ctrl-n	| Focus on the next pane |
| Focus pane previous | ctrl-k ctrl-p	| Focus on the previous pane |

## Editing

| Command | Linux | Description |
| ------- | ----- | ----------- |
| Duplicate Lines | `ctrl-shift-d` | Duplicates the line of the current cursor position and creates a new line under it with the same contents |
| Delete Line| `ctrl-shift-k` | Deletes the current line |
| Move Line Up | `ctrl-up` | Moves the contents of the current cursor position up one line. If there is a line above with content, the current lines content will swap with the one above it. |
| Move Line Down | `ctrl-down` | Moves the contents of the current cursor position down one line. If there is a line below with content, the line's content will swap with the one below it. |
| Find/Replace | `ctrl-f` | Opens up the Find/Replace panel |
| Find Next | `F3` | Toggles forward through the results of the current buffer in the file while the Find/Replace panel is active |
| Find Previous | `shift-F3` | Toggles backward through the results of the current buffer in the file while the Find/Replace panel is active|
| Find in Project | `ctrl-shift-f` | Opens the Find in Project Panel |
| Go To Line | `ctrl-g` | Opens the Go To Line panel |
| Go To Matching Bracket | `ctrl-m` | The cursor goes to the matching top bracket that the cursor is encapsulated in  |
| Select Line | `ctrl-l` | Selects the entire line the cursor's current position is in |
| Toggle Comment| `ctrl-/` | Toggles the selected text into a comment of the current grammar |



## apm

`apm` is Atom's package manager, based on Node's `npm` tool.

| Command | Description |
| ------- | ----------- |
| `apm upgrade` | Updates all locally installed packages |
| `apm upgrade --no-confirm` | Updates all locally installed packages without asking any questions |
| `apm stars --install` | Installs/updates all packages that you have marked as a favorite (_starred_) in your Atom.io profile |
| `apm publish minor` | If you're developing your own package, run this in the package's directory to publish a new version of the package, increasing the minor version number by one. |
