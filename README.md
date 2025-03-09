# Vim Pre Shortcut Keys

A VSCode extension that enhances your coding experience by providing preset shortcut keys to make VSCode feel more like Vim/Neovim.

## Features

- Preconfigured Vim-style keybindings
- Enhanced navigation shortcuts
- Integration with popular VSCode extensions
- Customized leader key settings
- Intuitive window management commands

## Keybindings

### Window Navigation

- `Ctrl + h` - Navigate to the left window (Normal mode)
- `Ctrl + l` - Navigate to the right window (Normal mode)
- `Ctrl + k` - Navigate to the window above (Normal mode)
- `Ctrl + j` - Navigate to the window below (Normal mode)
- `Ctrl + n` - Toggle sidebar visibility
- `|` - Split editor vertically (Normal mode)
- `\` - Split editor horizontally (Normal mode)

### File Explorer

- `Ctrl + n` - Focus file explorer
- `a` - Create new file
- `Shift + a` - Create new folder
- `o` - Open file/folder but not focus
- `r` - Rename file/folder
- `y` - Copy file/folder
- `p` - Paste file/folder
- `d` - Delete file/folder
- `s` - Open to side
- `x` - Cut file/folder
- `Shift + s` - Split editor down
- `Enter` - Open file or toggle folder

### Editor Navigation and Actions

- `Shift + j` - Move lines down (Visual Line mode)
- `Shift + k` - Move lines up (Visual Line mode)
- `Shift + k` - Show hover (Normal mode)
- `Ctrl + i` - Trigger suggestions (Insert mode)
- `Ctrl + p` - Show parameter hints (Insert mode)

### Quick Input/Suggestion Navigation

- `Ctrl + j` - Navigate to next item in:
  - File picker
  - Code actions
  - Suggestions
  - Quick input
  - Search
- `Ctrl + k` - Navigate to previous item in:
  - File picker
  - Code actions
  - Suggestions
  - Quick input
  - Search

### Hover Navigation

- `Ctrl + u` - Page up in hover
- `Ctrl + d` - Page down in hover
- `k` - Scroll up in hover
- `j` - Scroll down in hover
- `l` - Scroll right in hover
- `h` - Scroll left in hover

### Code Actions

- `Esc` - No highlight in normal mode
- `f` - EasyMotion
- `H` - Move to beginning of line
- `L` - Move to end of line
- `g + d` - Definition
- `g + p + d` - Peek Definition
- `g + I` - Implementation
- `g + p + I` - Peek Implementation
- `g + D` - Declaration
- `g + r` - References
- `g + R` - Find References
- `g + t` - Type Definition
- `g + p + t` - Peek Type Definition
- `g + L` - View problems
- `[ + d` - Previous diagnostic
- `] + d` - Next diagnostic
- `leader + a` - Code quickfix actions
- `leader + f + w` - Find in files
- `leader + f + r` - Replace in files
- `leader + f + k` - Open keybindings
- `leader + c` - Close active editor
- `leader + b + l` - Close left editors
- `leader + b + r` - Close right editors
- `leader + b + c` - Close other editors
- `leader + b + C` - Close all editors
- `leader + r + e` - Rename element
- `leader + r + f` - Rename file
- `leader + w` - Save file
- `leader + W` - Save all files
- `leader + q` - Quit file
- `leader + l` - Next Editor
- `leader + h` - Previous Editor

### Normal Mode Special Keys

- `:` - Show commands
- `;` - Quick open
- `jk` - Exit Insert mode (when typed quickly)

### Vim Configuration

- Leader key set to `<space>`
- Enabled features:
  - Show mode name
  - Incremental search
  - EasyMotion
  - Replace with register
  - Smart relative line
  - Surround
  - System clipboard integration
  - Highlighted yank (white text color)
  - Case-insensitive search with smart case

## Requirements

This extension depends on the following VSCode extensions:

- [Vim (vscodevim.vim)](https://marketplace.visualstudio.com/items?itemName=vscodevim.vim)

## Installation

1. Install VSCode
2. Install this extension from the VSCode Marketplace
3. Required extensions will be automatically installed as dependencies

## License

MIT

## Author

zykowal - [GitHub](https://github.com/zykowal)

## Acknowledgments

**Work with other plugins to get more powerful 🚀**

- [Toggle Boolean](https://marketplace.visualstudio.com/items?itemName=silesky.toggle-boolean)

```json
{
  "before": ["leader", "i"],
  "commands": ["extension.toggleBool"]
}
```

- [Bookmarks](https://marketplace.visualstudio.com/items?itemName=alefragnani.bookmarks)

```json
{
  "before": [ "leader", "m", "a" ],
  "commands": [ "bookmarks.toggle" ]
},
{
  "before": [ "leader", "m", "l" ],
  "commands": [ "bookmarks.list" ]
},
{
  "before": [ "leader", "m", "L" ],
  "commands": [ "bookmarks.listFromAllFiles" ]
},
{
  "before": [ "leader", "m", "c" ],
  "commands": [ "bookmarks.clear" ]
},
{
  "before": [ "leader", "m", "C" ],
  "commands": [ "bookmarks.clearFromAllFiles" ]
},
{
  "before": [ "leader", "m", "r" ],
  "commands": [ "bookmarks.refresh" ]
},
{
  "before": [ "[", "m" ],
  "commands": [ "bookmarks.jumpToPrevious" ]
},
{
  "before": [ "]", "m" ],
  "commands": [ "bookmarks.jumpToNext" ]
}
```

## Contributing

Feel free to submit issues and enhancement requests on the GitHub repository.

---

**Note**: This extension is designed to enhance your Vim experience in VSCode while maintaining compatibility with VSCode's native features.

**TIP**: If you don't like some shortcut keys, you can open keybindings.json or use `leader + f + k` to modify them. Enjoy it!😃
