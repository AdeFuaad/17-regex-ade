# REGEX FOR VALIDATING EMAIL ADDRESSES

In this tutorial, you'll learn how to use regex to validate email addresses. The following regex pattern will be used to check if an input string is a valid email address:


## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Look-ahead](#look-ahead)

## Regex Components

### Anchors

Anchors help you define the start and end positions of a pattern within the input string. In our regex, we use `^` and `$` as anchors. The `^` symbol signifies the start of the string, while the `$` symbol represents the end of the string. 


### Quantifiers

Quantifiers specify the number of occurrences for a character or group. In our regex, we use the quantifiers `{1,254}`, `{1,64}`, and `{1,255}` to set limits on the length of the email address and its components.


### Character Classes

Character classes help define a set of characters that can match a single character within the input string. In our regex, we use `[a-z0-9_-]` and `[a-z]` as character classes.


### Flags

Flags modify the behavior of the regex pattern. In our regex, we use the `i` flag to make the pattern case-insensitive.


### Grouping and Capturing

Grouping and capturing combine multiple regex components into a single unit. In our regex, we use `()` for grouping and capturing.


### Look-ahead

Look-ahead checks if a particular pattern exists further in the input string without actually consuming any characters. In our regex, we use `(?=.{1,254})`, `(?=.{1,64}@.{1,255}$)` and `(?=\S)` as positive look-aheads.


## Author

[Fuaad Shobambi github](https://github.com/adefuaad)

Please make revisions to the tutorial in the GitHub gist UI so that graders have access to your revision history.
