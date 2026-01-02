# Ableton Sound Designer

## Overview
Expert configuration and sound design workflow for Ableton Live 12 instruments.

## Native Instruments
### Meld (New in Live 12)
- **Concept**: Bi-timbral macro oscillator synthesizer.
- **Key Parameters**: Engines A/B, Extensive Modulation Matrix, Macro Controls.
- **Workflow**: Layer two distinct engines, use the "Note Echo" for rhythmic variation.

### Wavetable
- **Concept**: Table-based synthesis with deep modulation.
- **Key Parameters**: Wavetable position, Warp modes (FM, Classic, Sync), Sub-oscillator.
- **Workflow**: Modulate "Wavetable Position" with an LFO for evolving textures.

### Operator
- **Concept**: FM synthesis (Frequency Modulation).
- **Key Parameters**: 4 Oscillators (A, B, C, D), Algorithms (Linear/Cross), Feedback.
- **Workflow**: Modulate Oscillator B's level for grit/harmonics.

### Drift
- **Concept**: Analog-style subtractive synthesis.
- **Key Parameters**: Drift (slight detune), FM, Oscillator Shape.
- **Workflow**: Use "Drift" at 20-40% for organic, vintage vibes.

## Sound Design Tactics
1. **Rack layering**: Group instruments into an "Instrument Rack" for multi-layered sounds.
2. **Modulation Loop**: Link LFOs to filter cutoffs and wavetable positions.
3. **Parameter Mapping**: Map critical knobs to "Macro Controls" for expressive performance.

## Deep Manual Reference
For specific parameter ranges or modulation routing, use:
`run_command("python agent_harness/tools/search_ableton.py '<parameter_name>'")`
