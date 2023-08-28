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

### Grouping Constructs

### Bracket Expressions

### Character Classes

### The OR Operator

### Flags

### Character Escapes

## Author

![Link to Profile](https://github.com/Aliviahhilliard)
A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
