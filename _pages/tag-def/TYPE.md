---
title: TYPE
permalink: /terms/v7/TYPE.html
layout: none
redirect-from:
  - /terms/v7/TYPE
...

```

%YAML 1.2
---
lang: en-US

type: structure

uri: https://gedcom.io/terms/v7/TYPE

standard tag: 'TYPE'

specification:
  - Type
  - |
    A descriptive word or phrase used to further classify the superstructure.
    
    When both a `NOTE` and free-text `TYPE` are permitted as substructures of the
    same structure, the displaying systems should always display the `TYPE` value
    when they display the data from the associated structure; `NOTE` will typically
    be visible only in a detailed view.
    
    `TYPE` must be used whenever the generic `EVEN`, `FACT` and `IDNO` tags are
    used. It may also be used for any other event or attribute.
    
    Using the subordinate `TYPE` classification method provides a further
    classification of the superstructure but does not change its basic meaning.
    
    <div class="example">
    
    A `ORDN` with a `TYPE` could clarify what kind of ordination was performed:
    
    ```gedcom
    0 @I1@ INDI
    1 ORDN
    2 TYPE Bishop
    ```
    
    This classifies the entry as an ordination as a bishop, which is still a
    ordination event. The event could be further clarified with `RELI`, `DATE`, and
    other substructures.
    
    Other descriptor values might include, for example,
    
    - "Stillborn" as a qualifier to `BIRT` (birth)
    - "Civil" as a qualifier to `MARR` (marriage)
    - "College" as a qualifier to `GRAD` (graduation)
    - "Oral" as a qualifier to `WILL`
    
    See also `FACT` and `EVEN` for additional examples.
    
    </div>

label: 'Type'

payload: http://www.w3.org/2001/XMLSchema#string

substructures: {}

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
  "https://gedcom.io/terms/v7/FAM-EVEN": "{1:1}"
  "https://gedcom.io/terms/v7/FAM-FACT": "{1:1}"
  "https://gedcom.io/terms/v7/FAM-NCHI": "{0:1}"
  "https://gedcom.io/terms/v7/FAM-RESI": "{0:1}"
  "https://gedcom.io/terms/v7/FCOM": "{0:1}"
  "https://gedcom.io/terms/v7/GRAD": "{0:1}"
  "https://gedcom.io/terms/v7/IDNO": "{1:1}"
  "https://gedcom.io/terms/v7/IMMI": "{0:1}"
  "https://gedcom.io/terms/v7/INDI-CENS": "{0:1}"
  "https://gedcom.io/terms/v7/INDI-EVEN": "{1:1}"
  "https://gedcom.io/terms/v7/INDI-FACT": "{1:1}"
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
  "https://gedcom.io/terms/v7/REFN": "{0:1}"
  "https://gedcom.io/terms/v7/RETI": "{0:1}"
  "https://gedcom.io/terms/v7/SSN": "{0:1}"
  "https://gedcom.io/terms/v7/WILL": "{0:1}"

contact: "https://gedcom.io/community/"
...

```
