---
title: ADR3
permalink: /terms/v7/ADR3.html
layout: none
redirect-from:
  - /terms/v7/ADR3
...

```

%YAML 1.2
---
lang: en-US

type: structure

uri: https://gedcom.io/terms/v7/ADR3

standard tag: 'ADR3'

specification:
  - Address Line 3
  - |
    The third line of the address, used for indexing. This structure's payload
    should be a single line of text equal to the third line of the corresponding
    `ADDR`. See `ADDRESS_STRUCTURE` for more details.
    
    <div class="deprecation">
    
    `ADR3` should not be added to new files; see `ADDRESS_STRUCTURE` for more
    details.
    
    </div>

label: 'Address Line 3'

payload: http://www.w3.org/2001/XMLSchema#string

substructures: {}

superstructures:
  "https://gedcom.io/terms/v7/ADDR": "{0:1}"

contact: "https://gedcom.io/community/"
...

```
