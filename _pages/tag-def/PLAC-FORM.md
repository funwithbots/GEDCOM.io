---
title: PLAC-FORM
permalink: /terms/v7/PLAC-FORM.html
layout: none
redirect-from:
  - /terms/v7/PLAC-FORM
...

```

%YAML 1.2
---
lang: en-US

type: structure

uri: https://gedcom.io/terms/v7/PLAC-FORM

standard tag: 'FORM'

specification:
  - Format
  - |
    A comma-separated list of jurisdictional titles, which has the same number of
    elements and in the same order as the `PLAC` structure. As with `PLAC`, this
    shall be ordered from lowest to highest jurisdiction.
    
    <div class="example">
    
    The following represents Baltimore, a city that is not within a county.
    
    ```gedcom
    2 PLAC Baltimore, , Maryland, USA
    3 FORM City, County, State, Country
    ```
    
    </div>

label: 'Format'

payload: https://gedcom.io/terms/v7/type-List#Text

substructures: {}

superstructures:
  "https://gedcom.io/terms/v7/PLAC": "{0:1}"

contact: "https://gedcom.io/community/"
...

```
