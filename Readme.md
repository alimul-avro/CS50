# GitHub Dark Theme (CS50 Style)

This setting makes the **GitHub Dark theme** in VS Code look exactly like the **CS50 IDE** version.  
Simply paste the configuration below into your VS Code settings.

## 🛠 Installation

1. Open VS Code
2. Press `Ctrl + ,` (or `Cmd + ,` on macOS) to open Settings
3. Click the "Open Settings (JSON)" icon in the top-right corner
4. Paste the following code inside your `settings.json`:

```json
"workbench.colorCustomizations": {
    "[GitHub Dark Default]": {
        // This is CS50 style :)
        "activityBar.activeBorder": "#f78166",
        "activityBar.background": "#000000",
        "activityBar.border": "#30363d",
        "activityBar.foreground": "#e6edf3",
        "activityBar.inactiveForeground": "#7d8590",
        "activityBarBadge.background": "#1f6feb",
        "activityBarBadge.foreground": "#ffffff",
        "badge.background": "#1f6feb",
        "badge.foreground": "#ffffff",
        // ... (rest of your theme settings)
        "terminal.ansiYellow": "#d29922",
        "terminal.background": "#000000",
        "terminal.foreground": "#ffffff",
        "textBlockQuote.background": "#010409",
        "textBlockQuote.border": "#30363d",
        "textCodeBlock.background": "#6e768166",
        "textLink.activeForeground": "#2f81f7",
        "textLink.foreground": "#2f81f7",
        "textPreformat.foreground": "#7d8590",
        "textSeparator.foreground": "#21262d",
        "titleBar.activeBackground": "#0d1117",
        "titleBar.activeForeground": "#7d8590",
        "titleBar.border": "#30363d",
        "titleBar.inactiveBackground": "#010409",
        "titleBar.inactiveForeground": "#7d8590",
        "tree.indentGuidesStroke": "#21262d"
    }
}