---
title: LANG
permalink: /terms/v7/LANG.html
layout: none
redirect-from:
  - /terms/v7/LANG
...

```

%YAML 1.2
---
lang: en-US

type: structure

uri: https://gedcom.io/terms/v7/LANG

standard tag: 'LANG'

specification:
  - Language
  - |
    The primary human language of the superstructure. The primary language in which
    the `Text`-typed payloads of the superstructure and its substructures appear.
    
    The payload of the `LANG` structure is a language tag, as defined by [BCP 47].
    A [registry of component subtags] is maintained publicly by the IANA.
    
    In the absence of a `LANG` structure, the language is assumed to be
    unspecified; that may also be recorded explicitly with language tag `und`
    (meaning "undetermined"). See `https://gedcom.io/terms/v7/HEAD-LANG` for
    information about applying language-specific algorithms to text in an
    unspecified language.
    
    If the text is primarily in one language with a few parts in a different
    language, it is recommended that a language tag identifying the primary
    language be used. If no one language is primary, the language tag `mul`
    (meaning "multiple") may be used, but most language-specific algorithms will
    treat `mul` the same way they do `und`.
    
    <div class="note">
    
    Conversations are ongoing about adding part-of-payload language tagging in a
    future version of the specification to provide more fidelity for multilingual
    text.
    
    </div>
    
    If the text is not in any human language and should not be treated as lingual
    content, the language tag `zxx` (meaning "no linguistic content" or "not
    applicable") may be used. An example of `zxx` text might be a diagram
    approximated using characters for their shape, not their meaning.
    
    <div class="note">
    
    This specification does not permit `LANG` in every place where human language
    text might appear. Conversations are ongoing about adding it in more places in
    a future version of the specification. Using the current specification,
    additional language tagging can be accomplished using a [documented extension
    tag] by including the following in the header:
    
    ```gedcom
    1 SCHEMA
    2 TAG _LANG https://gedcom.io/terms/v7/LANG
    ```
    
    and using the extension tag like so:
    
    ```gedcom
    2 DATE 31 AUG 2018
    3 PHRASE 2018年8月31日
    4 _LANG cmn
    ```
    
    </div>

label: 'Language'

payload: http://www.w3.org/2001/XMLSchema#Language

substructures: {}

superstructures:
  "https://gedcom.io/terms/v7/NAME-TRAN": "{1:1}"
  "https://gedcom.io/terms/v7/NOTE": "{0:1}"
  "https://gedcom.io/terms/v7/NOTE-TRAN": "{0:1}"
  "https://gedcom.io/terms/v7/PLAC": "{0:1}"
  "https://gedcom.io/terms/v7/PLAC-TRAN": "{1:1}"
  "https://gedcom.io/terms/v7/TEXT": "{0:1}"
  "https://gedcom.io/terms/v7/record-SNOTE": "{0:1}"

contact: "https://gedcom.io/community/"
...

```
