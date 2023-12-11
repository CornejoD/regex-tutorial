# Title (replace with your title)

Introductory paragraph (replace this with your text)

## Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.

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

^[\w\.-]+@[a-zA-Z\d\.-]+\.[a-zA-Z]{2,}$

### Anchors

 The anchor tag `^` represents the start of the string and everything that follows must fit the specified parameters

 The anchor tag `$` represents the end of the string and everything prior to it must also fit the specified parameters

### Quantifiers

`+` matches one or more occurences of the preceding character or group
`{2,}` matches at least 2 occurences of the preceding character or group

### Grouping Constructs

`([\w\.-]+)` capturing group for the local part of the email
`([a-zA-Z\d\.-]+)` capturing group for the domain part of the email

### Bracket Expressions

`[\w\.-]` matches any word character (`\w`), dot (`.`), or hyphen (`-`).

### Character Classes

`\w` matches any word character
`\d` matches any digit

### The OR Operator

No OR Operator used here but can be used to provide alternatives

### Flags

`i` case-insensitive flag

### Character Escapes

`\.` escapes the dot treating it as a literal character

## Author

Diego Cornejo has been in the coding journey for a bit more than two years. Starting with C++ and now learning JavaScript. Hoping to learn more languages but also deepen his knowledge in his current state.
[Github-Profile](https://github.com/CornejoD)
