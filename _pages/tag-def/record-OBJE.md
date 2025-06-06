---
title: record-OBJE
permalink: /terms/v7/record-OBJE.html
layout: none
redirect-from:
  - /terms/v7/record-OBJE
...

```

%YAML 1.2
---
lang: en-US

type: structure

uri: https://gedcom.io/terms/v7/record-OBJE

standard tag: 'OBJE'

specification:
  - Object
  - See `MULTIMEDIA_RECORD`.
  - |
    The multimedia record refers to 1 or more external digital files, and may
    provide some additional information about the files and the media they encode.
    
    The file reference can occur more than once to group multiple files together.
    Grouped files should each pertain to the same context. For example, a sound
    clip and a photo both of the same event might be grouped in a single `OBJE`.
    
    The change and creation dates should be for the `OBJE` record itself, not the
    underlying files.

label: 'Object'

payload: null

substructures:
  "https://gedcom.io/terms/v7/CHAN": "{0:1}"
  "https://gedcom.io/terms/v7/CREA": "{0:1}"
  "https://gedcom.io/terms/v7/EXID": "{0:M}"
  "https://gedcom.io/terms/v7/FILE": "{1:M}"
  "https://gedcom.io/terms/v7/NOTE": "{0:M}"
  "https://gedcom.io/terms/v7/REFN": "{0:M}"
  "https://gedcom.io/terms/v7/RESN": "{0:1}"
  "https://gedcom.io/terms/v7/SNOTE": "{0:M}"
  "https://gedcom.io/terms/v7/SOUR": "{0:M}"
  "https://gedcom.io/terms/v7/UID": "{0:M}"

superstructures: {}

contact: "https://gedcom.io/community/"
...

```
