---
title: INDI-RESI
permalink: /terms/v7/INDI-RESI.html
layout: none
redirect-from:
  - /terms/v7/INDI-RESI
...

```

%YAML 1.2
---
lang: en-US

type: structure

uri: https://gedcom.io/terms/v7/INDI-RESI

standard tag: 'RESI'

specification:
  - Residence
  - |
    An [Individual Attribute]. See also `INDIVIDUAL_ATTRIBUTE_STRUCTURE`.
    
    Where possible, the residence should be identified in `PLAC` and/or `ADDR`
    substructures of the `RESI` structure. The payload text should not duplicate
    `PLAC` or `ADDR` information, but may be used for residence information that
    cannot be expressed by those structures.
    
    <div class="example">
    
    The following two examples show situations where a `RESI` payload may be
    appropriate:
    
    ```gedcom
    1 RESI living with an aunt
    2 DATE ABT MAR 1894
    ```
    
    ```gedcom
    1 RESI in a mobile caravan
    2 PLAC , , Austro-Hungarian Empire
    3 FORM City, County, Country
    ```
    
    </div>
  - residence
  - An address or place of residence where an individual resided.

label: 'Residence'

payload: http://www.w3.org/2001/XMLSchema#string

substructures:
  "https://gedcom.io/terms/v7/ADDR": "{0:1}"
  "https://gedcom.io/terms/v7/AGE": "{0:1}"
  "https://gedcom.io/terms/v7/AGNC": "{0:1}"
  "https://gedcom.io/terms/v7/ASSO": "{0:M}"
  "https://gedcom.io/terms/v7/CAUS": "{0:1}"
  "https://gedcom.io/terms/v7/DATE": "{0:1}"
  "https://gedcom.io/terms/v7/EMAIL": "{0:M}"
  "https://gedcom.io/terms/v7/FAX": "{0:M}"
  "https://gedcom.io/terms/v7/NOTE": "{0:M}"
  "https://gedcom.io/terms/v7/OBJE": "{0:M}"
  "https://gedcom.io/terms/v7/PHON": "{0:M}"
  "https://gedcom.io/terms/v7/PLAC": "{0:1}"
  "https://gedcom.io/terms/v7/RELI": "{0:1}"
  "https://gedcom.io/terms/v7/RESN": "{0:1}"
  "https://gedcom.io/terms/v7/SDATE": "{0:1}"
  "https://gedcom.io/terms/v7/SNOTE": "{0:M}"
  "https://gedcom.io/terms/v7/SOUR": "{0:M}"
  "https://gedcom.io/terms/v7/TYPE": "{0:1}"
  "https://gedcom.io/terms/v7/UID": "{0:M}"
  "https://gedcom.io/terms/v7/WWW": "{0:M}"

superstructures:
  "https://gedcom.io/terms/v7/record-INDI": "{0:M}"

contact: "https://gedcom.io/community/"
...

```
