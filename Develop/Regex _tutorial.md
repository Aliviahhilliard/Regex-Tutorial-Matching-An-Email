# Regex Matching an Email Tutorial

# Understanding the Regex: `/^(?=.*[a-z])(?=.*[A-Z])(?=.*\d)[a-zA-Z\d]{8,}$/`

We're delving into a common regex pattern that validates email addresses. This regex ensures the password is at least 8 characters long, contains at least one lowercase letter, one uppercase letter, and one number. Regex code snippet: `/^(?=.*[a-z])(?=.*[A-Z])(?=.*\d)[a-zA-Z\d]{8,}$/`.

## Summary

The Regular Expression: `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/` is designed to validate email addresses. The expression consists of three primary segments, which are:

1. Local Part: `([a-z0-9_\.-]+)`
    - Matches lowercase alphabets, digits, underscores, hyphens, and dots one or more times.
  
2. Domain: `([\da-z\.-]+)`
    - Matches digits and lowercase alphabets, as well as hyphens and dots one or more times.

3. Top-Level Domain: `([a-z\.]{2,6})`
    - Matches lowercase alphabets and dots between 2 to 6 times.

The caret `^` and dollar `$` signs indicate the start and end of the string, respectively, ensuring a complete match.

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

The regular expression for matching an email is /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/.

### Anchors

Anchors match a position within a string, not the characters themselves. The primary symbols are:

^: Matches the beginning of a string
$: Matches the end of a string
\b: Matches a word boundary
\B: Matches a non-word boundary

### Quantifiers

Quantifiers define the number of occurrences for a particular element.

bob|alice: Matches 'bob' or 'alice'
z?: Zero or one occurrences
z*: Zero or more occurrences
z+: One or more occurrences
z{n}: Exactly n occurrences
z{min,max}: Between min and max occurrences

### Grouping Constructs

Grouping constructs can capture substrings or apply quantifiers to entire patterns.

### Bracket Expressions

[xyz] match any x, y, z
[J-Z] match any capital letters between J & Z.
[^xyz] NOT x, y, z

### Character Classes

Character classes provide shorthand for sets of characters.

\w: Matches a word character
\d: Matches a digit
\s: Matches whitespace (tabs, line breaks)
\W: Matches a non-word character
\D: Matches a non-digit character
\S: Matches a non-whitespace character
\t: Matches a tab
\n: Matches a line break
.: Matches any character except a newline

### The OR Operator

`|` is the OR Operator, which allows a match to have a match x or y component.

### Flags

Flags alter the behavior of the entire regular expression. The basic format is /expression/flags, such as /[A-Z]+/g.

### Character Escapes

Special characters can be escaped using backslashes, as in /hello\?\*\\/.

## Author

Aliviah Hilliard is a mom to three amazing kiddos, genealogist and now avid coding student.
![Link to Profile](https://github.com/Aliviahhilliard)
