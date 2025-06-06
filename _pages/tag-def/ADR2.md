---
title: ADR2
permalink: /terms/v7/ADR2.html
layout: none
redirect-from:
  - /terms/v7/ADR2
...

```

%YAML 1.2
---
lang: en-US

type: structure

uri: https://gedcom.io/terms/v7/ADR2

standard tag: 'ADR2'

specification:
  - Address Line 2
  - |
    The second line of the address, used for indexing. This structure's payload
    should be a single line of text equal to the second line of the corresponding
    `ADDR`. See `ADDRESS_STRUCTURE` for more details.
    
    <div class="deprecation">
    
    `ADR2` should not be added to new files; see `ADDRESS_STRUCTURE` for more
    details.
    
    </div>

label: 'Address Line 2'

payload: http://www.w3.org/2001/XMLSchema#string

substructures: {}

superstructures:
  "https://gedcom.io/terms/v7/ADDR": "{0:1}"

contact: "https://gedcom.io/community/"
...

```
