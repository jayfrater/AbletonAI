# Ableton Assistant

## Overview
Expert knowledge base for troubleshooting and optimizing Ableton Live.

## Common Solutions
### Audio Crackles / Dropouts
1. **Buffer Size**: Increase buffer (Preferences > Audio). Use powers of 2 (128, 256, 512).
2. **Sample Rate**: Lower to 44.1kHz or 48kHz.
3. **High Performance**: Set Windows Power Plan to "High Performance".
4. **Drivers**: Ensure ASIO drivers are selected (not MME/DirectX).

### VST Issues
1. **Scanning**: Disable "Rescan Plug-ins on Startup" in File/Folder preferences if generic scan hangs.
2. **Crash**: If Live crashes on scan, hold `Alt` while launching to disable VSTs, then identify the bad plugin.
3. **Folders**: Keep 64-bit VST2 and VST3 in separate, clean folders.

### CPU Optimization
1. **Freeze**: Right-click track > Freeze Track to render effects.
2. **Flatten**: Convert frozen track to audio permanently.

## Deep Manual Search
If the solution is not listed here, use the `ableton_knowledge_base` skill to search the official manual:
`run_command("python agent_harness/tools/search_ableton.py '<query>'")`
