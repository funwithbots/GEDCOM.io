---
title: type-Name
permalink: /terms/v7/type-Name.html
layout: none
redirect-from:
  - /terms/v7/type-Name
...

```

%YAML 1.2
---
lang: en-US

type: data type

uri: https://gedcom.io/terms/v7/type-Name

specification:
  - |
    A personal name is mostly free-text. It should be the name as written in the
    culture of the individual and should not contain line breaks, repeated spaces,
    or characters not part of the written form of a name (except for U+002F as
    explained below).
    
    ```abnf
    PersonalName = nameStr
                 / [nameStr] "/" [nameStr] "/" [nameStr]
    
    nameChar     = %x20-2E / %x30-10FFFF  ; any but '/' and '\t'
    nameStr      = 1*nameChar
    ```
    
    The character U+002F (`/`, slash or solidus) has special meaning in a personal
    name, being used to delimit the portion of the name that most closely matches
    the concept of a surname, family name, or the like. This specification does not
    provide any standard way of representing names that contain U+002F.
    
    The URI for the `PersonalName` data type is
    `https://gedcom.io/terms/v7/type-Name`.

contact: "https://gedcom.io/community/"
...

```
