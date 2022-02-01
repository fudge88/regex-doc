# Regular Expression (RegEx)

A regular expression, or regex for short- is a shorthand representation for a set of strings.

## Summary

The following RegEx is a short and precise pattern that completely describes the set of string.
For example if there was a list of standard vehicle registration plates:

```
DA71FBC
KM20WTJ
PY66HZG
```

A RegEx would allow you to check whether a string is a valid vehicle registration plate, by checking the string against the pattern.

```
(^[A-Z]{2}[0-9]{2} [A-Z]{3}$)
```

When a vehicle Registration is compared to the above RegEx, this will return a boolean response `true || false` indicating whether the string belongs to the vehicle registration RegEx pattern or not.

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

### Anchors

### Quantifiers

### Grouping Constructs

### Bracket Expressions

### Character Classes

### The OR Operator

### Flags

### Character Escapes

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
