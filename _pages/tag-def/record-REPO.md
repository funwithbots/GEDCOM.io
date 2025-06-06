---
title: record-REPO
permalink: /terms/v7/record-REPO.html
layout: none
redirect-from:
  - /terms/v7/record-REPO
...

```

%YAML 1.2
---
lang: en-US

type: structure

uri: https://gedcom.io/terms/v7/record-REPO

standard tag: 'REPO'

specification:
  - Repository
  - See `REPOSITORY_RECORD`.
  - |
    The repository record provides information about an institution or person that
    has a collection of sources. Informal repositories include the owner of an
    unpublished work or of a rare published source, or a keeper of personal
    collections. An example would be the owner of a family Bible containing
    unpublished family genealogical entries.
    
    Layered repositories, such as an archive containing copies of a subset of
    records from another archive or archives that have moved or been bought by
    other archives, are not modeled in this version of the specification. It is
    expected they will be added in a later version. Until such time, it is
    recommended that the repository record store current contact information, if
    known.

label: 'Repository'

payload: null

substructures:
  "https://gedcom.io/terms/v7/ADDR": "{0:1}"
  "https://gedcom.io/terms/v7/CHAN": "{0:1}"
  "https://gedcom.io/terms/v7/CREA": "{0:1}"
  "https://gedcom.io/terms/v7/EMAIL": "{0:M}"
  "https://gedcom.io/terms/v7/EXID": "{0:M}"
  "https://gedcom.io/terms/v7/FAX": "{0:M}"
  "https://gedcom.io/terms/v7/NAME": "{1:1}"
  "https://gedcom.io/terms/v7/NOTE": "{0:M}"
  "https://gedcom.io/terms/v7/PHON": "{0:M}"
  "https://gedcom.io/terms/v7/REFN": "{0:M}"
  "https://gedcom.io/terms/v7/SNOTE": "{0:M}"
  "https://gedcom.io/terms/v7/UID": "{0:M}"
  "https://gedcom.io/terms/v7/WWW": "{0:M}"

superstructures: {}

contact: "https://gedcom.io/community/"
...

```
