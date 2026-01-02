# Ableton Mixing Expert

## Overview
Advanced mixing, routing, and signal processing workflows in Ableton Live 12.

## Core Effects
### Roar (New in Live 12)
- **Concept**: Dynamic saturator and distortion.
- **Workflow**: Use "Multi-band" mode to distort only the mid-highs while keeping the low end clean.
- **Tactic**: Modulate the "Amount" with an LFO for rhythmic movement.

### Glue Compressor
- **Concept**: Analog-modeled bus compressor for cohesion.
- **Workflow**: Set "Soft Clip" to ON for saturation. Use a slow attack and moderate release to "glue" drums together.

### EQ Eight
- **Concept**: Standard surgical EQ.
- **Workflow**: Enable "Mid/Side" mode to EQ the stereo field separately from the center. High-pass (Cut) the sides below 100Hz for a tighter mix.

### Hybrid Reverb
- **Concept**: Convolution + Algorithmic reverb.
- **Workflow**: Use convolution for realistic space and the "Shimmer" mode for ambient tails.

## Mixing Workflows
1. **Parallel Processing**: Use "Audio Effect Racks" to create separate chains (wet/dry) for heavy processing without losing clarity.
2. **Sidechain Compression**: Link the compressor on your Bass track to the Kick drum for "ducking."
3. **Gain Staging**: Maintain -6dB to -12dB of headroom on individual tracks before hitting the Master bus.

## Master Bus Chain
1. **EQ Eight** (Low cut/High shelf)
2. **Glue Compressor** (1-2dB reduction)
3. **Limiter** (To prevent clipping)

## Deep Manual Reference
For signal flow diagrams or detailed effect parameters, use:
`run_command("python agent_harness/tools/search_ableton.py '<effect_name>'")`
