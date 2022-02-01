# Regular Expression (RegEx)

A regular expression, or regex (regexp, or r.e) for short- is a shorthand representation for a set of strings.

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

Implementation of RegExs differ to suit the need for the expression. Although, sometimes a character has a relatively universal use. Below are some regular expression components. Consider a search operation for digits on a multi-line text. The pattern `[0–9]` finds every digit in the text, no matter where it is located.

### Anchors

Anchors are characters that specify the location within a particular string to search.

For example:
The pattern `^[0–9]` finds every digit that is the first character on a line.

<span style="color:red">`1`</span>`2 3 4`

The same idea applies to line endings with `[0–9]$`.

`1 2 3`<span style="color:red">`4`</span>

Some more examples of anchors that do not consume characters:

```
^: Beginning of string (or line, depending on the mode)
$: End of string (or line, depending on the mode)
\A: Beginning of string
\z: End of string
\Z: Varies a lot depending on the engine, so be careful with it
\b: Word boundary
\B: Not a word boundary
```

### Quantifiers

### Grouping Constructs

### Bracket Expressions

### Character Classes

### The OR Operator

### Flags

### Character Escapes

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
