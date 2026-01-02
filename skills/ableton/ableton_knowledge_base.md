# Ableton Knowledge Base

## Overview
Access the full "Ableton Live 12 Reference Manual" (955 pages) to answer deep technical questions.

## Tools
### search_ableton_manual
- **Description**: Search the official manual for any feature, shortcut, or concept.
- **Args**: `query` (string) - The term to search for (e.g., "Comping", "MPE", "Groove Pool").
- **Usage**:
    ```python
    result = run_command("python agent_harness/tools/search_ableton.py 'Groove Pool'")
    ```

## When to use
- If `ableton_maestro` or `ableton_assistant` doesn't have the answer.
- For specific parameter details (e.g., "What does the Spread parameter in Wavetable do?").
- For lookup of niche shortcuts not in the main list.
