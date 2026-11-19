# bin-interior-styling

A Claude-compatible skill package for controlled interior-render editing.

## Contents

- `SKILL.md` — main instructions and two-step workflow.
- `references/STYLE_PROFILE.md` — aesthetic guidance and reference-image rules.
- `references/DO_NOT_CHANGE.md` — design-lock checklist.
- `references/QUALITY_CHECK.md` — before/after verification checklist.
- `SOURCE_NOTES.md` — provenance and reconstruction notes.
- `assets/approved_examples/` — approved reference examples.
- `assets/rejected_examples/` — failed or disallowed examples.

## Use

1. Place the `bin-interior-styling` folder in the skills directory configured for
   your Claude environment.
2. Invoke `bin-interior-styling` when editing an interior render.

For each task, provide the current base render, any marked edit region, reference
images with their intended roles, the exact requested change, and any physical
dimensions or installation direction.

The current base image controls geometry and composition. Reference images guide
only the attributes assigned to them. User instructions define the permitted edit.
