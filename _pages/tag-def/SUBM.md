---
title: SUBM
permalink: /terms/v7/SUBM.html
layout: none
redirect-from:
  - /terms/v7/SUBM
...

```

%YAML 1.2
---
lang: en-US

type: structure

uri: https://gedcom.io/terms/v7/SUBM

standard tag: 'SUBM'

specification:
  - Submitter
  - A contributor of information in the substructure. This is metadata about the
    structure itself, not data about its subject.

label: 'Submitter'

payload: "@<https://gedcom.io/terms/v7/record-SUBM>@"

substructures: {}

superstructures:
  "https://gedcom.io/terms/v7/HEAD": "{0:1}"
  "https://gedcom.io/terms/v7/record-FAM": "{0:M}"
  "https://gedcom.io/terms/v7/record-INDI": "{0:M}"

contact: "https://gedcom.io/community/"
...

```
