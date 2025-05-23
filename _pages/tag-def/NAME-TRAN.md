---
title: NAME-TRAN
permalink: /terms/v7/NAME-TRAN.html
layout: none
redirect-from:
  - /terms/v7/NAME-TRAN
...

```

%YAML 1.2
---
lang: en-US

type: structure

uri: https://gedcom.io/terms/v7/NAME-TRAN

standard tag: 'TRAN'

specification:
  - Translation
  - |
    A type of `TRAN` substructure specific to [Personal Names]. Each `NAME`.`TRAN`
    must have a `LANG` substructure. See also `INDI`.`NAME`.
    
    <div class="example">
    
    The following presents a name in Mandarin, transliterated using Pinyin
    
    ```gedcom
    1 NAME /孔/德庸
    2 GIVN 德庸
    2 SURN 孔
    2 TRAN /Kǒng/ Déyōng
    3 GIVN Déyōng
    3 SURN Kǒng
    3 LANG zh-pinyin
    ```
    
    </div>
  - |
    A representation of the superstructure's data in a different format.
    
    In some situations it is desirable to provide the same semantic content in
    multiple formats. Where this is desirable, a `TRAN` substructure is used, where
    the specific format is given in its language tag substructure, media type
    substructure, or both.
    
    Different `TRAN` structures are used in different contexts to fully capture the
    structure of the information being presented in multiple formats. In all cases,
    a `TRAN` structure's payload and substructures should provide only information
    also contained in the `TRAN` structures' superstructure, but provide it in a
    new language, script, or media type.
    
    Each `TRAN` substructure must have either a language tag or a media type or
    both. Each `TRAN` structure must differ from its superstructure and from every
    other `TRAN` substructure of its superstructure in either its language tag or
    its media type or both.

label: 'Translation'

payload: https://gedcom.io/terms/v7/type-Name

substructures:
  "https://gedcom.io/terms/v7/GIVN": "{0:M}"
  "https://gedcom.io/terms/v7/LANG": "{1:1}"
  "https://gedcom.io/terms/v7/NICK": "{0:M}"
  "https://gedcom.io/terms/v7/NPFX": "{0:M}"
  "https://gedcom.io/terms/v7/NSFX": "{0:M}"
  "https://gedcom.io/terms/v7/SPFX": "{0:M}"
  "https://gedcom.io/terms/v7/SURN": "{0:M}"

superstructures:
  "https://gedcom.io/terms/v7/INDI-NAME": "{0:M}"

contact: "https://gedcom.io/community/"
...

```
