# AliceOS Error Database
A central database for all error codes found in AliceOS

## Features
- Includes for all distributions of AliceOS
- Defines possible causes for error and solutions
- Easy to use and navigate

## Adding a custom error
Create a Jekyll markdown file and use the following as a template:
```md
---
date: (put in date of writing)
title: ERROR_CODE
categories:
description: 
deprecated: 
type: 

provider: Default
provider_email: admin@aliceos.app

error_type: Fatal
version_affected: 
version_deprecate: 
---
## Cause of Error


## Possible Solutions

```

Please make a pull request for review by the AliceOS team.