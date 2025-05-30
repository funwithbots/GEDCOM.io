---
title: LONG
permalink: /terms/v7/LONG.html
layout: none
redirect-from:
  - /terms/v7/LONG
...

```

%YAML 1.2
---
lang: en-US

type: structure

uri: https://gedcom.io/terms/v7/LONG

standard tag: 'LONG'

specification:
  - Longitude
  - |
    A longitudinal coordinate. The payload is either `E` (for a coordinate east of
    the prime meridian) or `W` (for a coordinate west of the prime meridian)
    followed by a decimal number of degrees. Minutes and seconds are not used and
    should be converted to fractional degrees prior to encoding.
    
    <div class="example">
    
    168 degrees, 9 minutes, and 3.4 seconds East would be formatted as
    `E168.150944`.
    
    </div>

label: 'Longitude'

payload: http://www.w3.org/2001/XMLSchema#string

substructures: {}

superstructures:
  "https://gedcom.io/terms/v7/MAP": "{1:1}"

contact: "https://gedcom.io/community/"
...

```
