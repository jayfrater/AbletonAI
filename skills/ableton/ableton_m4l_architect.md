# Ableton Max for Live (M4L) Architect

## Overview
Guidance for building custom instruments and effects using Max for Live in Ableton Live 12.

## Device Types
- **Max MIDI Effect**: Processes incoming MIDI data.
- **Max Audio Effect**: Processes incoming audio data.
- **Max Instrument**: Generates audio from MIDI data.

## Live API Objects (LOM)
The Live Object Model (LOM) allows M4L devices to communicate with the application:
- `live.path`: Navigate to specific tracks, devices, or parameters (e.g., `path live_set tracks 0`).
- `live.observer`: Monitor parameter changes in real-time.
- `live.remote~`: High-performance remote control of parameters.
- `live.object`: Get/set properties or call functions (e.g., `call fire` on a Clip).

## Development Best Practices
1. **Abstraction**: Use sub-patchers (`p` or `bpatcher`) to keep your main UI clean.
2. **Standardization**: Use `live.*` objects (e.g., `live.gain~`, `live.dial`) for UI elements to match Ableton's look and feel.
3. **CPU Efficiency**: Disable heavy processing when the device is not receiving audio/MIDI.
4. **JavaScript**: Use the `js` object for complex logic or procedural pattern generation that is difficult in Max's visual language.

## Common Max Objects
- `m4l.api`: Helpful abstraction for common LOM tasks.
- `m4l.chooser`: UI element to select tracks/devices.
- `plug-in~`: External audio input for Audio Effects.

## Deep Manual Reference
For LOM hierarchy diagrams or specific API function names, use:
`run_command("python agent_harness/tools/search_ableton.py 'Max for Live API'")`
