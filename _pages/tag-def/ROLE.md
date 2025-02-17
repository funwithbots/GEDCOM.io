---
title: ROLE
permalink: /terms/v7/ROLE.html
layout: none
redirect-from:
  - /terms/v7/ROLE
...

```

%YAML 1.2
---
lang: en-US

type: structure

uri: https://gedcom.io/terms/v7/ROLE

standard tag: ROLE

specification:
  - Role
  - |
    An enumerated value from set https://gedcom.io/terms/v7/enumset-ROLE
    indicating what role this person played in an event or person’s life.
    
    The following indicates a child’s birth record as the source of the
    mother’s name:
    
        0 @I1@ INDI
        1 NAME Mary //
        2 SOUR @S1@
        3 EVEN BIRT
        4 ROLE MOTH
    
    The following indicates that a person’s best friend was a witness at their
    baptism:
    
        0 @I2@ INDI
        1 ASSO @I3@
        2 ROLE FRIEND
        3 PHRASE best friend
        1 BAPM
        2 ASSO @I3@
        3 ROLE WITN

payload: https://gedcom.io/terms/v7/type-Enum

enumeration set: "https://gedcom.io/terms/v7/enumset-ROLE"

substructures:
  "https://gedcom.io/terms/v7/PHRASE": "{0:1}"

superstructures:
  "https://gedcom.io/terms/v7/ASSO": "{1:1}"
  "https://gedcom.io/terms/v7/SOUR-EVEN": "{0:1}"
...

```
