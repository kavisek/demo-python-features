# Jupyter Notebooks

## Working with Notebooks in  VSCode

Update your settings.json with the following confiugration values to have VSCOde use the poetry virtual environment for the notebooks.

```json 
{
    "workbench.colorCustomizations": {
        "activityBar.background": "#143041",
        "titleBar.activeBackground": "#1C445B",
        "titleBar.activeForeground": "#F7FAFD"
    }, 
    "python.defaultInterpreterPath": "${workspaceFolder}/notebooks/.venv/bin/python",
}
```
