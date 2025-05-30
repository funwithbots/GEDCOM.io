---
title: HEAD-LANG
permalink: /terms/v7/HEAD-LANG.html
layout: none
redirect-from:
  - /terms/v7/HEAD-LANG
...

```

%YAML 1.2
---
lang: en-US

type: structure

uri: https://gedcom.io/terms/v7/HEAD-LANG

standard tag: 'LANG'

specification:
  - Language
  - |
    A default language which may be used to interpret any `Text`-typed payloads
    that lack a specific language tag from a `https://gedcom.io/terms/v7/LANG`
    structure. An application may choose to use a different default based on its
    knowledge of the language preferences of the user.
    
    The payload of the `LANG` structure is a language tag, as defined by [BCP 47].
    
    <div class="note">
    
    Some algorithms on text are language-specific. Examples include sorting
    sequences, name comparison and phonetic name matching algorithms,
    spell-checking, computer-synthesized speech, Braille transcription, and
    language translation. When the language of the text is given through a
    `https://gedcom.io/terms/v7/LANG`, that should be used. When
    `https://gedcom.io/terms/v7/LANG` is not available,
    `https://gedcom.io/terms/v7/HEAD-LANG` provides the file creator's suggested
    default language. For some language-specific algorithms, the user's preferred
    language may be a more appropriate default than the file's default language.
    User language preferences can be found in a variety of platform-specific
    places, such as the default language from operating system settings, user
    locales, Input Method Editors (IMEs), etc.
    
    </div>

label: 'Language'

payload: http://www.w3.org/2001/XMLSchema#Language

substructures: {}

superstructures:
  "https://gedcom.io/terms/v7/HEAD": "{0:1}"

contact: "https://gedcom.io/community/"
...

```
