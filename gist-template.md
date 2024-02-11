## Regex Assignment

This README provides a comprehensive overview of various components of regular expressions (regex) and their functionalities. Each section explains a specific aspect of regex with examples and use cases.

## Summary

This assignment covers a wide range of regex components, including anchors, quantifiers, the OR operator, character classes, flags, grouping and capturing, bracket expressions, greedy and lazy matching, boundaries, back-references, and look-ahead and look-behind assertions. Understanding these regex components is essential for effective text processing and pattern matching.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components

### Anchors

Anchors are regex symbols used to specify the position of a pattern in a string. They include:

- **^ (caret):** Matches the start of a line or string.
- **$ (dollar sign):** Matches the end of a line or string.
- **\b (word boundary):** Matches a position where a word begins or ends.
- **\B (non-word boundary):** Matches a position that is not a word boundary.
- **\A (start of string):** Matches the start of a string.
- **\Z (end of string):** Matches the end of a string.
- **\z (absolute end of string):** Matches the absolute end of a string.

Anchors are useful for validating input or extracting specific patterns from text.

### Quantifiers

Quantifiers specify the number of occurrences of a character or group in a regex pattern. Common quantifiers include:

- **? (Question mark):** Matches zero or one occurrence of the preceding element.
- **\* (Asterisk):** Matches zero or more occurrences of the preceding element.
- **+ (Plus):** Matches one or more occurrences of the preceding element.
- **{n} (Exact quantifier):** Matches exactly n occurrences of the preceding element.
- **{n,} (Minimum quantifier):** Matches at least n occurrences of the preceding element.
- **{n,m} (Range quantifier):** Matches between n and m occurrences of the preceding element, inclusive.
- **{n}? {n,}? {n,m}? (Lazy quantifiers):** Makes the preceding quantifier lazy, matching as few characters as possible.

Quantifiers allow for flexible matching patterns in text processing tasks.

### OR Operator

The OR operator (|) in regex allows you to specify alternatives within a pattern. It matches either the expression before or after it.

### Character Classes

Character classes, also known as character sets or ranges, allow you to specify a set of characters that you want to match within a pattern. They are enclosed in square brackets ([]).

### Flags

Flags modify the behavior of regex patterns. Common flags include:

- **i (ignore case):** Matches patterns regardless of case.
- **g (global):** Matches all occurrences of a pattern, not just the first one.
- **m (multiline):** Allows ^ and $ to match the start and end of each line.
- **s (dotAll):** Allows the dot (.) to match newline characters.
- **u (unicode):** Enables full Unicode support.
- **y (sticky):** Matches only at the position indicated by the lastIndex property.

Flags are appended to the end of regex literals to specify different matching options.

### Grouping and Capturing

Grouping and capturing allow you to match and extract substrings within a pattern. They are denoted by parentheses ().

### Bracket Expressions

Bracket expressions, also known as character classes, specify a set of characters to match within a pattern. They are enclosed in square brackets ([]).

### Greedy and Lazy Match

Greedy matching consumes as much text as possible, while lazy matching consumes as little as possible. They are specified using quantifiers (*, +, ?) followed by a question mark (?).

### Boundaries

Boundaries define exact positions or limits within a string where a pattern can match. They include the start (^) and end ($) of a line, word boundaries (\b, \B), and the start (\A) and end (\Z, \z) of a string.

### Back-references

Back-references allow you to refer back to previously matched groups within a pattern. They are denoted by \ followed by the group number.

### Look-ahead and Look-behind

Look-ahead and look-behind assertions allow you to match a pattern only if it is followed by or preceded by another pattern, without including the lookahead or lookbehind pattern in the match itself.

## Author

I am a coding student at Rutgers EDX. You can find more about my projects on my [GitHub](https://github.com/Nicholasdavis03)
