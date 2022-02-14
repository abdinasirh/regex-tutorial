# Matching an Email Regex-Tutorial

Regular expression is a sequence of characters that defines a specific search pattern and can be used to find certain patterns of characters within a string. they are also used to validate inputs. 

## Summary

The following example will be used throughout the tutorial and will describe the functionality of each component in the regex. The example I will be explaining is matching an Email regex.

Matching an Email:  – /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/




## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)


### Anchors

Anchor symbols include the caret and the dollar sign. in the regex code above ^ sign symbolizes the beginning of a string and $ sign symbolized the end of a string.
### Quantifiers

Quantifiers indicate that the preceding token must be matched a certain number of times. By default, quantifiers are greedy, and will match as many characters as possible. In the example above, {2,6} quantifier, matches the specified quantity of the previous token. {2,6} will match 2 to 6. the + matches 1 or more of the preceding token.
### Character Classes

Character classes match a character from a specific set. in our example above, [a-z] matches anything that falls between these two letters. \d Matches any digit character (0-9)
### Grouping and Capturing

Groups allow you to combine a sequence of tokens to operate on them together. Capture groups can be referenced by a backreference and accessed separately in the results. in the example above, we have 3 groups; ([a-z0-9_\.-]+), ([\da-z\.-]+) and ([a-z\.]{2,6}). 

### Bracket Expressions
Brackets indicate a set of characters to match. In our example above, we will
    1. [a-z0-9_\.-] indicates we are looking for lowercase a-z, 0-9 and so on.
    2. [\da-z\.-] indicates we are looking any digit 0-9, a-z and so on

## Author

Abdinasir Hassan a student at University of Minnesota bootcamp. You can reach me at

    [Github](https://github.com/abdinasirh)

