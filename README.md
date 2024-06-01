#  offnd.at vocabularies

This repository contains vocabularies used by [offnd.at](https://offnd.at) to create URLs.

## Vocabulary hierarchy

The folders in the repository are organized using following paths

```
/{language}/{offensiveness}/{grammaticalNumber}/{grammaticalGender}/{theme}/{partOfSpeech}.txt
```

where:
 - _**language**_ is [ISO 639-1](https://en.wikipedia.org/wiki/ISO_639-1) language code,
 - _**offensiveness**_ is one of `[offensive, non-offensive]`,
 - _**grammaticalNumber**_ is one of `[none, singular, plural]`,
 - _**grammaticalGender**_ is one of `[none, masculine, feminine, neuter, masculine-personal, non-masculine-personal]`,
 - _**theme**_ is one of `[none, proper-names, politicians]`
 - _**partOfSpeech**_ is one of `[adverbs, adjectives, nouns]`
   
Example:

```
/pl/offensive/plural/non-masculine-personal/none/adjectives.txt
```

## Contribution

Contributions to vocabularies increase the number of available combinations that offnd.at is able to generate and/or enable URL generation in a new language. They are highly appreciated!
