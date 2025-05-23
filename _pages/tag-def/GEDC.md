---
title: GEDC
permalink: /terms/v7/GEDC.html
layout: none
redirect-from:
  - /terms/v7/GEDC
...

```

%YAML 1.2
---
lang: en-US

type: structure

uri: https://gedcom.io/terms/v7/GEDC

standard tag: 'GEDC'

specification:
  - GEDCOM
  - |
    A container for information about the entire document.
    
    It is recommended that applications write `GEDC` with its required substructure
    `https://gedcom.io/terms/v7/GEDC-VERS` as the first substructure of `HEAD`.

label: 'GEDCOM'

payload: null

substructures:
  "https://gedcom.io/terms/v7/GEDC-VERS": "{1:1}"

superstructures:
  "https://gedcom.io/terms/v7/HEAD": "{1:1}"

contact: "https://gedcom.io/community/"
...

```
