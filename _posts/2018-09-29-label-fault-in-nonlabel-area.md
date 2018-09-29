---
date: 2018-09-29
title: LABEL_FAULT_IN_NONLABEL_AREA
description: LABEL_FAULT_IN_NONLABEL_AREA
deprecated: 1
type: RenPy

categories:
    - RenPy

provider: Default
provider_email: admin@aliceos.app

error_type: Minor
version_affected: 1.0.0beta2
version_deprecate: 1.0.0beta3
---
## Cause of error
Ren'Py attempted to call a label that either doesn't exist or is corrupted. This error is also typically thrown when a demo ends or when the end of a technical preview is reached.

This Stop error has been replaced with the more human-readable `CALL_MISSING_LABEL`.

## Possible solutions
- Check the game files for the correct scripts.
- Reinstall the game.