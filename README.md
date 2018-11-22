# My config for visual studio code workflow

Since I move from Sublime Text to Visual Studio Code for most of my works, so in this repo, I want to show and share my config for VS Code (including some settings and all the plugins) which satisfy me. I think maybe someone might find something helpful.

## Config

```json
{
    "gitlens.advanced.messages": {
        "suppressShowKeyBindingsNotice": true
    },
    "gitlens.historyExplorer.enabled": true,
    "workbench.colorTheme": "Ayu Mirage",
    "editor.fontSize": 14,
    "editor.minimap.enabled": false,
    "editor.lineHeight": 25,
    "editor.fontFamily": "Roboto Mono,Menlo, Monaco, 'Courier New', monospace",
    "vim.disableExtension": false,
    "python.linting.enabled": false,
    "breadcrumbs.enabled": true,
    "javascript.implicitProjectConfig.experimentalDecorators": true,
    "window.zoomLevel": 0,
    "go.formatTool": "goimports",
    "explorer.confirmDelete": false,
    "workbench.statusBar.visible": false,
    "workbench.activityBar.visible": false,
    "editor.lineNumbers": "off",
    "settings.cycle": [{
        "id": "lineNumbers",
        "values":[
            {
                "editor.lineNumbers": "off",
            },
            {
                "editor.lineNumbers": "on",
            }
        ]
    }
],
}
```


## Package

### Ayu theme
[Ayu](https://marketplace.visualstudio.com/items?itemName=teabyii.ayu) theme

### Bracket Pair Colorizer
[Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer)

### Docker
[Docker](https://marketplace.visualstudio.com/items?itemName=PeterJausovec.vscode-docker)

### GitLens
[GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)

### Go
[Go](https://marketplace.visualstudio.com/items?itemName=ms-vscode.Go)

### JSON Tools
[JSON Tools](https://marketplace.visualstudio.com/items?itemName=eriklynd.json-tools)

### MagicPython
[MagicPython]()

### Markdown Preview Enhanced

![Markdown Preview Enhanced](https://i.imgur.com/K8OOqT6.png)

### Paste JSON as Code

### Pretify JSON

### Python
[Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)

### Rest Client

![Rest Client](https://i.imgur.com/Emne2kK.png)

### TODO Highlight

### Vetur

### Vim

### vscode-random

### YAML Support by Red Hat

### Settings Cycler
[Settings Cycler](https://marketplace.visualstudio.com/items?itemName=hoovercj.vscode-settings-cycler)

**keybinding.json**

```json
    {
        "key": "cmd+shift+r",
        "command": "settings.cycle.lineNumbers",
        "when": "editorFocus"
    }
```

**settings.json**

```json
    "settings.cycle": [{
        "id": "lineNumbers",
        "values":[
            {
                "editor.lineNumbers": "off",
            },
            {
                "editor.lineNumbers": "on",
            }
        ]
    }
```
