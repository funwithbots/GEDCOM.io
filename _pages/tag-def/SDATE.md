---
title: SDATE
permalink: /terms/v7/SDATE.html
layout: none
redirect-from:
  - /terms/v7/SDATE
...

```

%YAML 1.2
---
lang: en-US

type: structure

uri: https://gedcom.io/terms/v7/SDATE

standard tag: 'SDATE'

specification:
  - Sort date
  - |
    A date to be used as a sorting hint. It is intended for use when the actual
    date is unknown, but the display order may be dependent on date.
    
    If both a `DATE` and `SDATE` are present in the same structure, the `SDATE`
    should be used for sorting and positioning while the `DATE` should be displayed
    as the date of the structure.
    
    `SDATE` and its substructures (including `PHRASE`, `TIME`, and any extension
    structures) should be used only as sorting hints, not to convey historical
    meaning.
    
    It is recommended to use a payload that matches
    `[[day D] month D] year [D epoch]`. Other DateValue forms may have unreliable
    effects on sorting. Including a month and day is encouraged to help different
    applications sort dates the same way, as the relative ordering of dates with
    different levels of precision is not well defined.

label: 'Sort date'

payload: https://gedcom.io/terms/v7/type-Date

substructures:
  "https://gedcom.io/terms/v7/PHRASE": "{0:1}"
  "https://gedcom.io/terms/v7/TIME": "{0:1}"

superstructures:
  "https://gedcom.io/terms/v7/ADOP": "{0:1}"
  "https://gedcom.io/terms/v7/ANUL": "{0:1}"
  "https://gedcom.io/terms/v7/BAPM": "{0:1}"
  "https://gedcom.io/terms/v7/BARM": "{0:1}"
  "https://gedcom.io/terms/v7/BASM": "{0:1}"
  "https://gedcom.io/terms/v7/BIRT": "{0:1}"
  "https://gedcom.io/terms/v7/BLES": "{0:1}"
  "https://gedcom.io/terms/v7/BURI": "{0:1}"
  "https://gedcom.io/terms/v7/CAST": "{0:1}"
  "https://gedcom.io/terms/v7/CHR": "{0:1}"
  "https://gedcom.io/terms/v7/CHRA": "{0:1}"
  "https://gedcom.io/terms/v7/CONF": "{0:1}"
  "https://gedcom.io/terms/v7/CREM": "{0:1}"
  "https://gedcom.io/terms/v7/DEAT": "{0:1}"
  "https://gedcom.io/terms/v7/DIV": "{0:1}"
  "https://gedcom.io/terms/v7/DIVF": "{0:1}"
  "https://gedcom.io/terms/v7/DSCR": "{0:1}"
  "https://gedcom.io/terms/v7/EDUC": "{0:1}"
  "https://gedcom.io/terms/v7/EMIG": "{0:1}"
  "https://gedcom.io/terms/v7/ENGA": "{0:1}"
  "https://gedcom.io/terms/v7/FAM-CENS": "{0:1}"
  "https://gedcom.io/terms/v7/FAM-EVEN": "{0:1}"
  "https://gedcom.io/terms/v7/FAM-FACT": "{0:1}"
  "https://gedcom.io/terms/v7/FAM-NCHI": "{0:1}"
  "https://gedcom.io/terms/v7/FAM-RESI": "{0:1}"
  "https://gedcom.io/terms/v7/FCOM": "{0:1}"
  "https://gedcom.io/terms/v7/GRAD": "{0:1}"
  "https://gedcom.io/terms/v7/IDNO": "{0:1}"
  "https://gedcom.io/terms/v7/IMMI": "{0:1}"
  "https://gedcom.io/terms/v7/INDI-CENS": "{0:1}"
  "https://gedcom.io/terms/v7/INDI-EVEN": "{0:1}"
  "https://gedcom.io/terms/v7/INDI-FACT": "{0:1}"
  "https://gedcom.io/terms/v7/INDI-NCHI": "{0:1}"
  "https://gedcom.io/terms/v7/INDI-RELI": "{0:1}"
  "https://gedcom.io/terms/v7/INDI-RESI": "{0:1}"
  "https://gedcom.io/terms/v7/INDI-TITL": "{0:1}"
  "https://gedcom.io/terms/v7/MARB": "{0:1}"
  "https://gedcom.io/terms/v7/MARC": "{0:1}"
  "https://gedcom.io/terms/v7/MARL": "{0:1}"
  "https://gedcom.io/terms/v7/MARR": "{0:1}"
  "https://gedcom.io/terms/v7/MARS": "{0:1}"
  "https://gedcom.io/terms/v7/NATI": "{0:1}"
  "https://gedcom.io/terms/v7/NATU": "{0:1}"
  "https://gedcom.io/terms/v7/NMR": "{0:1}"
  "https://gedcom.io/terms/v7/OCCU": "{0:1}"
  "https://gedcom.io/terms/v7/ORDN": "{0:1}"
  "https://gedcom.io/terms/v7/PROB": "{0:1}"
  "https://gedcom.io/terms/v7/PROP": "{0:1}"
  "https://gedcom.io/terms/v7/RETI": "{0:1}"
  "https://gedcom.io/terms/v7/SSN": "{0:1}"
  "https://gedcom.io/terms/v7/WILL": "{0:1}"

contact: "https://gedcom.io/community/"
...

```
