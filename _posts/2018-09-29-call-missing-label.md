---
date: 2018-09-29
title: CALL_MISSING_LABEL
description: CALL_MISSING_LABEL
deprecated: 0
type: RenPy

categories:
    - RenPy

provider: Default
provider_email: admin@aliceos.app

error_type: Minor
version_affected: 1.0.0beta3+
---
## Cause of Error
Ren'Py attempted to call new label which doesn't exist in the mod. This often appears when you have completed the mod and there are no more labels to call to.

## Possible Solutions
- Mod developers can disable this feature as shown [here](https://i.imgur.com/cnRIhoQ.png).
