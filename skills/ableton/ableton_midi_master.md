# Ableton MIDI Master

## Overview
Expertise in MIDI sequencing, generative tools, and MPE (MIDI Polyphonic Expression) in Ableton Live 12.

## MIDI Tools & Generators (New in Live 12)
### Generators
- **Rhythm**: Create rhythmic patterns automatically within a clip.
- **Stacks**: Generate chords and harmonized lines.
- **Seed**: Generates random MIDI notes based on constraints.
- **Workflow**: Click "Generate" in the Clip View to populate an empty MIDI clip with these tools.

### Transformations
- **Arpeggiate**: Sophisticated arpeggiation patterns applied directly to MIDI clips.
- **Strum**: Give chords a guitar-like strumming feel by staggering note starts.
- **Time Warp**: Stretch or compress MIDI timing within a selection.
- **Workflow**: Select MIDI notes > Apply Transformation via the sidebar in Clip View.

## Probability & Variation
- **Note Probability**: Set the likelihood (0-100%) of a note playing on each pass of the loop.
- **Velocity Range**: Define a range for random velocity fluctuations to add human feel.

## MPE (MIDI Polyphonic Expression)
- **Concept**: Individual control for every note in a chord (Pitch Bend, Pressure, Slide).
- **Supported Instruments**: Wavetable, Meld, Sampler.
- **Workflow**: Enable MPE in the Clip View > Use the "Expression" tab to draw modulation for specific notes.

## MIDI Effects
1. **Arpeggiator**: Real-time MIDI pattern generation.
2. **Chord**: Add up to 6 pitch offsets to single notes.
3. **Random**: Randomize incoming MIDI pitches within a scale.

## Deep Manual Reference
For complex chord stack math or MPE routing diagrams, use:
`run_command("python agent_harness/tools/search_ableton.py '<midi_topic>'")`
