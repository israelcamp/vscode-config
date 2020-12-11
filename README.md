# vscode-config

## Plugins
  - Bracket Pair Colorizer
  - Prettier
  - Path intellisense
  - ESLint
  - markdownlint
  - Markdown Preview Enhanced
  - Python
  - Visual Studio IntelliCode
  - VSCode Great Icons
  - YAML
  - GraphQL
  - GitLens - Git supercharged
  - Docker
  - Pylance 
  
 ## Settings
 
 ```json
 {
  "python.pythonPath": "/home/israel/miniconda3/bin/python3",
  "python.linting.pylintArgs": ["--disable=R,C,W", "--max-line-length=1000"],
  "workbench.colorCustomizations": {
    "statusBar.background": "#005eeb",
    "statusBar.noFolderBackground": "#dd0707",
    "statusBar.debuggingBackground": "#62ce0a"
  },
  "editor.semanticTokenColorCustomizations": {
    "[Monokai]": {
      "enabled": true,
      "rules": {
        "support.function.declaration:python": "#A6E22E",
        "class.declaration:python": {
          "foreground": "#A6E22E",
          "underline": false
        },
        "selfParameter": {
          "foreground": "#FD971F",
          "fontStyle": "bold"
        },
        "class.typeHint.builtin:python": {
          "foreground": "#66D9EF",
          "fontStyle": "italic"
        },
        "class.builtin:python": {
          "foreground": "#66D9EF",
          "fontStyle": "italic"
        },
        "class:python": { "foreground": "#66D9EF", "fontStyle": "" },
        "module:python": { "foreground": "#8968f7f8", "fontStyle": "" },
        "*.function.magic:python": "#66D9EF",
        "*.decorator:python": "#00dd12",
        "class.decorator.builtin:python": "#00dd12",
        "*.typeHint:python": "#5500aa",
        "*.typeHintComment:python": "#aaaaaa"
      }
    }
  },

  "git.ignoreMissingGitWarning": true,
  "window.zoomLevel": 1,
  "editor.fontSize": 14,
  "editor.multiCursorModifier": "ctrlCmd",
  "editor.snippetSuggestions": "top",
  "breadcrumbs.enabled": false,
  "python.jediEnabled": false,
  "workbench.iconTheme": "vscode-great-icons",
  "git.autofetch": true,
  "editor.fontLigatures": true,
  "workbench.colorTheme": "Monokai",
  "python.dataScience.sendSelectionToInteractiveWindow": true,
  "editor.suggestSelection": "first",
  "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
  "editor.formatOnPaste": true,
  "editor.formatOnSave": true,
  "python.languageServer": "Pylance"
}
 ```
