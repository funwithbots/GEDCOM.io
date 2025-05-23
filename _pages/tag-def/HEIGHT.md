---
title: HEIGHT
permalink: /terms/v7/HEIGHT.html
layout: none
redirect-from:
  - /terms/v7/HEIGHT
...

```

%YAML 1.2
---
lang: en-US

type: structure

uri: https://gedcom.io/terms/v7/HEIGHT

standard tag: 'HEIGHT'

specification:
  - Height in pixels
  - |
    How many pixels to display vertically for the image. See `CROP` for more
    details.
    
    <div class="note">
    
    `HEIGHT` is a number of pixels. The correct tag for the height of an individual
    is the `DSCR` attribute.
    
    <div class="example">
    
    ```gedcom
    0 @I45@ INDI
    1 DSCR brown eyes, 5ft 10in, 198 pounds
    ```
    
    </div>
    
    </div>

label: 'Height in pixels'

payload: http://www.w3.org/2001/XMLSchema#nonNegativeInteger

substructures: {}

superstructures:
  "https://gedcom.io/terms/v7/CROP": "{0:1}"

contact: "https://gedcom.io/community/"
...

```
