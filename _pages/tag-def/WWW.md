---
title: WWW
permalink: /terms/v7/WWW.html
layout: none
redirect-from:
  - /terms/v7/WWW
...

```

%YAML 1.2
---
lang: en-US

type: structure

uri: https://gedcom.io/terms/v7/WWW

standard tag: 'WWW'

specification:
  - Web address
  - |
    A URL or other locator for a World Wide Web page of the subject of the
    superstructure, as defined by any relevant standard such as [whatwg/url], [RFC
    3986], [RFC 3987], and so forth.
    
    Like other substructures, the `WWW` structure provides details about the
    subject of its superstructure. For example, a `MARR`.`WWW` is a world wide web
    page of the marriage event, not the personal website of the couple or an entry
    in an online database serving as a source documenting the marriage. However,
    the meaning of `WWW` was only implicit when it was introduced in version 5.5.1
    and many files were created that use `WWW` to store a more tangentially-related
    web address, so applications are recommended to interpret the `WWW` structure's
    meaning cautiously.
    
    If an invalid or no longer existing web address is present upon import, it
    should be preserved as-is on export.

label: 'Web address'

payload: http://www.w3.org/2001/XMLSchema#string

substructures: {}

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
  "https://gedcom.io/terms/v7/CORP": "{0:M}"
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
  "https://gedcom.io/terms/v7/SSN": "{0:M}"
  "https://gedcom.io/terms/v7/WILL": "{0:M}"
  "https://gedcom.io/terms/v7/record-REPO": "{0:M}"
  "https://gedcom.io/terms/v7/record-SUBM": "{0:M}"

contact: "https://gedcom.io/community/"
...

```
