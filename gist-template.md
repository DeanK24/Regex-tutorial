# Regex Tutorial

A regex, which is short for regular expression, is a sequence of characters that defines a specific search pattern. When included in code or search algorithms, regular expressions can be used to find certain patterns of characters within a string, or to find and replace a character or sequence of characters within a string. They are also frequently used to validate input.

## Summary

/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

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

### Anchors
Anchors inform us that the engine's current position in the string matches a determined location: for example, the beginning of the string/line, or the end of a string/line.
^ is put in the beginning and $ is put at the end.

### Quantifiers
Quantifiers specify how many instances of a character, group, or character class must be present in the input for a match to be found. + and {} would be the quantifiers in this example. + means that the pattern can be matched one or more times. {} means that there are multiple definitions depending on the characters inside the curly brackets.

### Character Classes
A character class is a set of characters enclosed within square brackets. It specifies the characters that will successfully match a single character from a given input string. A character escape uses a backslash meaning the characters inside the square bracket are wrong. 

### Grouping and Capturing
A group is a part of a regex pattern enclosed in parentheses () metacharacter. We create a group by placing the regex pattern inside the set of parentheses ( and ) . Capturing groups are a way to treat multiple characters as a single unit. They are created by placing the characters to be grouped inside a set of parentheses. This example has 3 different sets of parantheses. The username, the email provider, and the .com.

### Bracket Expressions
A bracket expression is either a matching list expression or a non-matching list expression. It consists of one or more expressions: ordinary characters, collating elements, collating symbols, equivalence classes, character classes, or range expressions. So when you see that it means that it is searching through a-z. Example [a-z].

### Greedy and Lazy Match
The standard quantifiers in regular expressions are greedy, meaning they match as much as they can, only giving back as necessary to match the remainder of the regex. By using a lazy quantifier, the expression tries the minimal match first.

## Author

Made by Dean Ketchmark
GitHub Link: https://github.com/DeanK24
