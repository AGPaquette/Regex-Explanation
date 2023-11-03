# Regex

Regular expressions is a tool that is used to make sure the text that is inputed matches the pattern that regex has specify. The regex pattern is a sequence of characters that define the pattern the user needs to input in order to move forweard. The tool is used frequently in order to search, match, and find information in text. The ctrl + F on windows is an example of a regex tool that a user can use to search for a word or words on a page.

## Summary

Example: ^([a-zA-Z0-9._%+-]+)@([a-zA-Z0-9.-]+)\.(com|org|net)$

The regex above will be used to validate someone's email address. It is checkiung for the format of an email adress.

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
 - ^: Anchors the match to the beginning of the line.
 - $: Anchors the match to the end of the line.

### Quantifiers
 - +: After [a-zA-Z0-9._%+-]+, it quantifies that the preceding character class can occur one or more times.

### Grouping Constructs
 - ( ): Parentheses are used to create capturing groups therer are two capture groups in the regex example.

### Bracket Expressions
- []: Within the character classes, square brackets define sets of characters that are allowed in the email address. For example, [a-zA-Z0-9] matches any uppercase or lowercase letter or digit and [-._%+] says that special characters like hyphen, dot, underscore, percent, and plus are also allowed in the local part

### Character Classes
 - [a-zA-Z]: Matches any uppercase or lowercase letter.
 - [0-9]: Matches any digit.

### The OR Operator
 - |: (com|org|net): This part specifies that the TLD can be one of three options: "com," "org," or "net." It uses the OR operator | to provide alternatives.
### Flags
- there are no flags in the regex because flags are used rto check for case sen

### Character Escapes
- There are no special character escapes used in this regex.

## Author

- Javascript and Python developer with a bachlors in economics. Enjoy looking at data and how coding helps make the workload of gathering data a lot easier.

