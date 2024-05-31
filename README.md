# Offnd.at vocabularies

This repository contains vocabularies used by [offnd.at](https://offnd.at) to create URLs.

## Vocabulary hierarchy

The folders in the repository are organized using following paths

```
/{language}/{offensiveness}/{grammaticalNumber}/{grammaticalGender}/{partOfSpeech}.txt
```

where:
 - _language_ is [ISO 639-1](https://en.wikipedia.org/wiki/ISO_639-1) language code,
 - _offensiveness_ is one of [_Offensive_, _NonOffensive_],
 - _grammaticalNumber_ is optional and, if present, one of [_Singular_, _Plural_],
 - _grammaticalGender_ is optional and, if present, one of [_Masculine_, _Feminine_, _Neuter_, _MasculinePersonal_, _NonMasculinePersonal_],
 - _partOfSpeech_ is one of [_Adverbs_, _Nouns_, _Adjectives_]
   - collections of nouns may be preceded with _{word}-_, where _word_ is noun's theme, e.g., `Politicians-Nouns.txt`
   
Example:

```
/pl/Offensive/Plural/NonMasculinePersonal/Adjectives.txt
```

## Contribution

Contributions to vocabularies increase the number of available combinations that offnd.at is able to generate and/or enable URL generation in a new language. They are highly appreciated!
