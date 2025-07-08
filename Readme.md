# GitHub Dark Theme (CS50 Style)

This setting makes the **GitHub Dark theme** in VS Code look exactly like the **CS50 IDE** version.  
Simply paste the configuration below into your VS Code settings.

## 🛠 Installation

Hi, I figured it out! So the theme is basically GitHub Dark Default with a few customizations. To add the customizations, you have to open up settings.json and add a few things.

Step 1: Set the theme to GitHub Dark Default.

Step 2: Press `Ctrl + Shift + P` and then type `Preferences: Open Settings (JSON)`

Step 3: Scroll down until you find `workbench.colorCustomizations` and then inside that you should paste this: 
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
