# VS Code Web Development Settings 🛠️

This `settings.json` configures **Visual Studio Code (VS Code)** for web development (HTML, CSS, JavaScript, TypeScript, JSX/TSX) using built-in features, replacing extensions like Auto Rename Tag, Auto Close Tag, and Bracket Pair Colorizer.

## Features

- **Auto Tags** 🔗: Auto-renames and closes HTML/JSX/TSX tags.
- **Auto Imports** 📥: Suggests and organizes imports for JavaScript/TypeScript.
- **Bracket Colorization** 🎨: Colors brackets and highlights indentation.
- **Emmet** ⚡: Speeds up HTML/JSX with abbreviations (e.g., `div>ul>li*3`).
- **Whitespace Trimming** ✂️: Removes trailing whitespace (except Markdown).
- **Italic Comments** *✨*: Styles comments in *italic* for readability.
- **Code Formatting** 📝: Auto-formats JSON, HTML, CSS, JS, and TS on save.

## Installation

1. **Locate Settings** 📂:
   - **Windows**: `C:\Users\<YourUsername>\AppData\Roaming\Code\User\settings.json`
   - **macOS**: `~/Library/Application Support/Code/User/settings.json`
   - **Linux**: `~/.config/Code/User/settings.json`
   - Or: Press `Ctrl+Shift+P`, type `Preferences: Open Settings (JSON)`, select it.

2. **Apply Settings** 🖌️:
   - Copy `settings.json` from this repository.
   - Paste into your `settings.json`, merging or replacing settings.
   - Save the file.

3. **Optional Theme** 🌙:
   - Suggested: Use `GitHub Dark` theme (`Ctrl+K Ctrl+T`) and [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme) extension for a better experience.
   - Recommended: Install [Fira Code](https://github.com/tonsky/FiraCode) font for italic comments.

## Notes ⚠️

- **Bracket Colors**: Custom bracket colors are set for `GitHub Dark`. Adjust `workbench.colorCustomizations` for other themes.
- **Emmet**: Try `lorem` or `div>p` in HTML/JSX files and press `Tab` to expand.