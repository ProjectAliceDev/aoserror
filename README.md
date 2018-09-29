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
date: 2018-09-29
title: ERR_CODE
categories:
    - 
description: ERR_CODE
type: Document
---
## Details
- Provider: Provider Name
- Type: (should match category)
- Applies to versions: (specific set of versions)

## Cause of error


## Possible solutions


```

Please make a pull request for review by the AliceOS team.