---
title: OBJE
permalink: /terms/v7/OBJE.html
layout: none
redirect-from:
  - /terms/v7/OBJE
...

```

%YAML 1.2
---
lang: en-US

type: structure

uri: https://gedcom.io/terms/v7/OBJE

standard tag: 'OBJE'

specification:
  - Object
  - See `MULTIMEDIA_LINK`.
  - |
    Links the superstructure to the `MULTIMEDIA_RECORD` with the given pointer.
    
    The optional `CROP` substructure indicates that a subregion of an image
    represents or applies to the superstructure.
    
    The optional `TITL` substructure supersedes any `OBJE.FILE.TITL` substructures
    included in the `MULTIMEDIA_RECORD`.

label: 'Object'

payload: "@<https://gedcom.io/terms/v7/record-OBJE>@"

substructures:
  "https://gedcom.io/terms/v7/CROP": "{0:1}"
  "https://gedcom.io/terms/v7/TITL": "{0:1}"

superstructures:
  "https://gedcom.io/terms/v7/ADOP": "{0:M}"
  "https://gedcom.io/terms/v7/ANUL": "{0:M}"
  "https://gedcom.io/terms/v7/BAPM": "{0:M}"
  "https://gedcom.io/terms/v7/BARM": "{0:M}"
  "https://gedcom.io/terms/v7/BASM": "{0:M}"
  "https://gedcom.io/terms/v7/BIRT": "{0:M}"
  "https://gedcom.io/terms/v7/BLES": "{0:M}"
  "https://gedcom.io/terms/v7/BURI": "{0:M}"
  "https://gedcom.io/terms/v7/CAST": "{0:M}"
  "https://gedcom.io/terms/v7/CHR": "{0:M}"
  "https://gedcom.io/terms/v7/CHRA": "{0:M}"
  "https://gedcom.io/terms/v7/CONF": "{0:M}"
  "https://gedcom.io/terms/v7/CREM": "{0:M}"
  "https://gedcom.io/terms/v7/DEAT": "{0:M}"
  "https://gedcom.io/terms/v7/DIV": "{0:M}"
  "https://gedcom.io/terms/v7/DIVF": "{0:M}"
  "https://gedcom.io/terms/v7/DSCR": "{0:M}"
  "https://gedcom.io/terms/v7/EDUC": "{0:M}"
  "https://gedcom.io/terms/v7/EMIG": "{0:M}"
  "https://gedcom.io/terms/v7/ENGA": "{0:M}"
  "https://gedcom.io/terms/v7/FAM-CENS": "{0:M}"
  "https://gedcom.io/terms/v7/FAM-EVEN": "{0:M}"
  "https://gedcom.io/terms/v7/FAM-FACT": "{0:M}"
  "https://gedcom.io/terms/v7/FAM-NCHI": "{0:M}"
  "https://gedcom.io/terms/v7/FAM-RESI": "{0:M}"
  "https://gedcom.io/terms/v7/FCOM": "{0:M}"
  "https://gedcom.io/terms/v7/GRAD": "{0:M}"
  "https://gedcom.io/terms/v7/IDNO": "{0:M}"
  "https://gedcom.io/terms/v7/IMMI": "{0:M}"
  "https://gedcom.io/terms/v7/INDI-CENS": "{0:M}"
  "https://gedcom.io/terms/v7/INDI-EVEN": "{0:M}"
  "https://gedcom.io/terms/v7/INDI-FACT": "{0:M}"
  "https://gedcom.io/terms/v7/INDI-NCHI": "{0:M}"
  "https://gedcom.io/terms/v7/INDI-RELI": "{0:M}"
  "https://gedcom.io/terms/v7/INDI-RESI": "{0:M}"
  "https://gedcom.io/terms/v7/INDI-TITL": "{0:M}"
  "https://gedcom.io/terms/v7/MARB": "{0:M}"
  "https://gedcom.io/terms/v7/MARC": "{0:M}"
  "https://gedcom.io/terms/v7/MARL": "{0:M}"
  "https://gedcom.io/terms/v7/MARR": "{0:M}"
  "https://gedcom.io/terms/v7/MARS": "{0:M}"
  "https://gedcom.io/terms/v7/NATI": "{0:M}"
  "https://gedcom.io/terms/v7/NATU": "{0:M}"
  "https://gedcom.io/terms/v7/NMR": "{0:M}"
  "https://gedcom.io/terms/v7/OCCU": "{0:M}"
  "https://gedcom.io/terms/v7/ORDN": "{0:M}"
  "https://gedcom.io/terms/v7/PROB": "{0:M}"
  "https://gedcom.io/terms/v7/PROP": "{0:M}"
  "https://gedcom.io/terms/v7/RETI": "{0:M}"
  "https://gedcom.io/terms/v7/SOUR": "{0:M}"
  "https://gedcom.io/terms/v7/SSN": "{0:M}"
  "https://gedcom.io/terms/v7/WILL": "{0:M}"
  "https://gedcom.io/terms/v7/record-FAM": "{0:M}"
  "https://gedcom.io/terms/v7/record-INDI": "{0:M}"
  "https://gedcom.io/terms/v7/record-SOUR": "{0:M}"
  "https://gedcom.io/terms/v7/record-SUBM": "{0:M}"

contact: "https://gedcom.io/community/"
...

```
