# vs_code
## extensions
- Atom Keymap
- Ayu
- Code runner
- Coverage Hutters
- GitLens
- HTML CSS Support
- HTML Snippets
- Jupter
- Kite
- Markdown Preview Enhanced
- One Dark Pro
- Python
- Python Docstring Generator
- Test Explorer UI
- Django
- 
## settings.json
```
{
    "workbench.iconTheme": "ayu",
    "window.zoomLevel": 1,
    "editor.formatOnSave": true,
    "code-runner.clearPreviousOutput": true,
    "code-runner.showExecutionMessage": false,
    "code-runner.saveFileBeforeRun": true,
    "code-runner.executorMap": {
        "python": "$pythonPath -u $fullFileName",
    },
    "atomKeymap.promptV3Features": true,
    "editor.multiCursorModifier": "ctrlCmd",
    "editor.formatOnPaste": true,
    "git.autofetch": true,
    "workbench.colorTheme": "One Dark Pro",
    "python.formatting.provider": "black",
    "workbench.editorAssociations": [
        {
            "viewType": "jupyter.notebook.ipynb",
            "filenamePattern": "*.ipynb"
        }
    ],
    "autoDocstring.docstringFormat": "numpy",
    "kite.showWelcomeNotificationOnStartup": false,
    "python.testing.pytestEnabled": false,
    "debug.console.historySuggestions": false,
    "terminal.integrated.fontFamily": "FiraCode NF"
}
```
'FiraCode NF' can be downloaded from [nerdfonts](https://www.nerdfonts.com/)
## keybindings.json

```
// Place your key bindings in this file to override the defaults
[
    {
        "key": "ctrl+shift+c",
        "command": "editor.action.addCommentLine",
        "when": "editorTextFocus && !editorReadonly"
    },
    {
        "key": "ctrl+shift+c",
        "command": "editor.action.commentLine",
        "when": "editorTextFocus && !editorReadonly"
    },
    {
        "key": "ctrl+shift+space",
        "command": "code-runner.run"
    },
]
```
