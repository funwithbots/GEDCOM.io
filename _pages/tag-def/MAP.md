---
title: MAP
permalink: /terms/v7/MAP.html
layout: none
redirect-from:
  - /terms/v7/MAP
...

```

%YAML 1.2
---
lang: en-US

type: structure

uri: https://gedcom.io/terms/v7/MAP

standard tag: 'MAP'

specification:
  - Map
  - |
    A representative point for a location, as defined by `LATI` and `LONG`
    substructures.
    
    Note that `MAP` provides neither a notion of accuracy (for example, the `MAP`
    for a birth event may be some distance from the point where the birth occurred)
    nor a notion of region size (for example, the `MAP` for a place "Belarus" may
    be anywhere within that nation's 200,000 square kilometer area).

label: 'Map'

payload: null

substructures:
  "https://gedcom.io/terms/v7/LATI": "{1:1}"
  "https://gedcom.io/terms/v7/LONG": "{1:1}"

superstructures:
  "https://gedcom.io/terms/v7/PLAC": "{0:1}"

contact: "https://gedcom.io/community/"
...

```
