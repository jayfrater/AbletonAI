# Ableton Maestro

## Overview
Control Ableton Live 11/12 via keyboard shortcuts.

## Key Bindings (Windows/Mac)
The Agent uses `computer_use` (key_press) to trigger these:

### Transport
- **Play/Stop**: `Space`
- **Record**: `F9`
- **Capture MIDI**: `Ctrl+Shift+C`
- **Toggle Loop**: `Ctrl+L`

### Views
- **Session/Arrange**: `Tab`
- **Device/Clip**: `Shift+Tab`
- **Toggle Mixer**: `Ctrl+Alt+M`
- **Browser**: `Ctrl+Alt+B`

### Editing
- **Duplicate**: `Ctrl+D`
- **Quantize**: `Ctrl+U`
- **Consolidate**: `Ctrl+J`
- **Split Clip**: `Ctrl+E`
- **Group Tracks**: `Ctrl+G`
- **Insert Audio Track**: `Ctrl+T`
- **Insert MIDI Track**: `Ctrl+Shift+T`

## Workflow
1. **Agent**: "Create a new MIDI track."
2. **Tool**: `computer.key_press("ctrl", "shift", "t")`

## Finding More Shortcuts
To find shortcuts for specific features (e.g. "Simpler", "Warping"), use:
`run_command("python agent_harness/tools/search_ableton.py 'shortcut'")`
