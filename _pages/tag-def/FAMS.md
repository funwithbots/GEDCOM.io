---
title: FAMS
permalink: /terms/v7/FAMS.html
layout: none
redirect-from:
  - /terms/v7/FAMS
...

```

%YAML 1.2
---
lang: en-US

type: structure

uri: https://gedcom.io/terms/v7/FAMS

standard tag: 'FAMS'

specification:
  - Family spouse
  - The family in which an individual appears as a partner. See `FAMILY_RECORD` for
    more details.

label: 'Family spouse'

payload: "@<https://gedcom.io/terms/v7/record-FAM>@"

substructures:
  "https://gedcom.io/terms/v7/NOTE": "{0:M}"
  "https://gedcom.io/terms/v7/SNOTE": "{0:M}"

superstructures:
  "https://gedcom.io/terms/v7/record-INDI": "{0:M}"

contact: "https://gedcom.io/community/"
...

```
