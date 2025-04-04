---
title: CORP
permalink: /terms/v7/CORP.html
layout: none
redirect-from:
  - /terms/v7/CORP
...

```

%YAML 1.2
---
lang: en-US

type: structure

uri: https://gedcom.io/terms/v7/CORP

standard tag: 'CORP'

specification:
  - Corporate name
  - The name of the business, corporation, or person that produced or commissioned
    the product.

label: 'Corporate name'

payload: http://www.w3.org/2001/XMLSchema#string

substructures:
  "https://gedcom.io/terms/v7/ADDR": "{0:1}"
  "https://gedcom.io/terms/v7/EMAIL": "{0:M}"
  "https://gedcom.io/terms/v7/FAX": "{0:M}"
  "https://gedcom.io/terms/v7/PHON": "{0:M}"
  "https://gedcom.io/terms/v7/WWW": "{0:M}"

superstructures:
  "https://gedcom.io/terms/v7/HEAD-SOUR": "{0:1}"

contact: "https://gedcom.io/community/"
...

```
