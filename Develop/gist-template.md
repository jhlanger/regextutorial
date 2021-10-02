# Title (replace with your title)

Introductory paragraph (replace this with your text)

## Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.

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
Anchors belong to the family of regex tokens that don't match any characters, but that assert something about the string or the matching process. Anchors assert that the engine's current position in the string matches a well-determined location: for instance, the beginning of the string, or the end of a line.

^The will match any string that starts with "The"
end$ will match a string that ends with "end"
^The end$ will match the exact string that starts with "The" and ends with "end"
roar matchs any string that has the text "roar" in it. 
### Quantifiers
quantifier matches the preceding element one or more times, but as few times as possible. It is the lazy counterpart of the greedy quantifier + . For example, the regular expression \b\w+?\ b matches one or more characters separated by word boundaries.

abc* matchs a string that has "ab" followed by zero or more c 
abc+ matchs a string that has "ab" followed by one or more c
abc? matchs a string that has "ab" followed by zero or one c 
abc{2} matchs a string that has ab follwed by 2 c's (abcc)
abc{2, } matchs a string that has ab followed by 2 or more C's (abccccc)
abc{2,5} matchs a string that has ab followed by 2 and up to 5 Cs

### OR Operator
With an "OR Operator" you can create regular expressions that use the OR logic by using |.
a(b|c) matchs a string that has an "a" and is followed by "b" or "c" (ab, ac)


### Character Classes
With a “character class”, also called “character set”, you can tell the regex engine to match only one out of several characters.

\d matchs a single character that is a digit (any number)
\w matches a alphanumeric character plus underscore. (any letter or number)
\s matchs a whitespace character, includes tabs and line breaks
. matchs any character 

### Flags

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
