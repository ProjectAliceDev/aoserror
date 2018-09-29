---
date: 2018-09-29
title: LABEL_FAULT_IN_NONLABEL_AREA
categories:
    - Minor
    - RenPy
    - Deprecated
description: LABEL_FAULT_IN_NONLABEL_AREA
deprecated: 1
type: RenPy
---
## Details
- Provider: Default
- Type: Minor
- Applies to versions: 1.0.0beta2

## Cause of error
Ren'Py attempted to call a label that either doesn't exist or is corrupted. This error is also typically thrown when a demo ends or when the end of a technical preview is reached.

This Stop error has been replaced with the more human-readable `CALL_MISSING_LABEL`.

## Possible solutions
- Check the game files for the correct scripts.
- Reinstall the game.