# Regex Matching an Email Tutorial

Introductory paragraph (replace this with your text)

## Summary

The Regular Expression: `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/` is designed to validate email addresses. The expression consists of three primary segments, which are:

1. Local Part: `([a-z0-9_\.-]+)`
    - Matches lowercase alphabets, digits, underscores, hyphens, and dots one or more times.
  
2. Domain: `([\da-z\.-]+)`
    - Matches digits and lowercase alphabets, as well as hyphens and dots one or more times.

3. Top-Level Domain: `([a-z\.]{2,6})`
    - Matches lowercase alphabets and dots between 2 to 6 times.

The caret `^` and dollar `$` signs indicate the start and end of the string, respectively, ensuring a complete match.

Would you like further clarification on any of the segments?

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## Regex Components

 Matching an Email:`/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

### Anchors

The Anchors are unique in that they match a position within a string, not a character.

Such as using the following symbols:

^ = beginning
$ = end
\b = word boundary
\B = not word boundary

### Quantifiers

bob|alice match bob or alice
z? zero or one occurrences
z* zero or multiple occurrences
z+ one or multiple occurrences
z{n} n occurrences
z{min,max} min/max occurrences

### Grouping Constructs

### Bracket Expressions

[xyz] match any x, y, z
[J-Z] match any capital letters between J & Z.
[^xyz] NOT x, y, z

### Character Classes

\w word \d digit \s whitespace (tabs, line breaks)
\W NOT word \D NOT digit \S NOT whitespace
\t tabs, \n line breaks
. any character (except newline)

### The OR Operator

`|` is the OR Operator, which allows a match to have a match x or y component.

### Flags

/ expression / flags, i.e /[A-Z]+/g basic format

### Character Escapes

/ hello\?\*\\/ escape special characters with backslashes

## Author

Aliviah Hilliard is a mom to three amazing kiddos, genealogist and now avid coding student.
![Link to Profile](https://github.com/Aliviahhilliard)
