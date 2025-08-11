# Argode RGD Syntax Highlighter

VS Code extension for syntax highlighting of `.rgd` visual novel script files used by the Argode/Ren'Gd engine.

## Features

- **Syntax Highlighting**: Full support for RGD script syntax
- **Ren'Py-like Experience**: Beautiful color themes for visual novel development
- **Smart Indentation**: Automatic indentation for labels, menus, and choices
- **Code Folding**: Collapsible label blocks

## Supported Syntax

### Labels
```rgd
label start:
    # Your story begins here
```

### Character Definitions
```rgd
character yuko "Yuko" color=#ffaa88
```

### Dialogue
```rgd
yuko "Hello, [player_name]!"
narrator "The story continues..."
```

### Commands
```rgd
show yuko happy at center with dissolve
scene bg_school with fade
jump next_scene
```

### Custom Commands
```rgd
wait 2.0
window shake intensity=5.0
screen_flash color=white duration=0.5
```

## Installation

1. Download the `.vsix` file
2. Open VS Code
3. Go to Extensions (Ctrl+Shift+X)
4. Click "..." → "Install from VSIX"
5. Select the downloaded file

## Version History

- **1.0.0**: Initial release with full RGD syntax support