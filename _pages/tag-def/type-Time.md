---
title: type-Time
permalink: /terms/v7/type-Time.html
layout: none
redirect-from:
  - /terms/v7/type-Time
...

```

%YAML 1.2
---
lang: en-US

type: data type

uri: https://gedcom.io/terms/v7/type-Time

specification:
  - |
    Time is represented on a 24-hour clock (for example, 23:00 rather than 11:00
    PM). It may be represented either in event-local time or in Coordinated
    Universal Time (UTC). UTC is indicated by including a `Z` (U+005A) after the
    time value; event-local time is indicated by its absence. When a time is used
    together with a `DateExact`, it is recommended that UTC time be used rather
    than event-local time.
    
    ```abnf
    Time     =  hour ":" minute [":" second ["." fraction]] [%s"Z"]
    
    hour     = DIGIT / ("0" / "1") DIGIT / "2" ("0" / "1" / "2" / "3")
    minute   = ("0" / "1" / "2" / "3" / "4" / "5") DIGIT
    second   = ("0" / "1" / "2" / "3" / "4" / "5") DIGIT
    fraction = 1*DIGIT
    ```
    
    <div class="note">
    
    The above grammar prohibits end-of-day instant `24:00:00` and leap-seconds. It
    allows both `02:50` and `2:50` as the same time.
    
    </div>
    
    The URI for the `Time` data type is `https://gedcom.io/terms/v7/type-Time`.

contact: "https://gedcom.io/community/"
...

```
