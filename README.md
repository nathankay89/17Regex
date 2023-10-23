#  Demystifying Regular Expressions
Regular expressions (regex) are powerful tools for pattern matching and text processing. This tutorial aims to simplify the understanding of regex for web development students. We will explore the core components of regex, breaking down each element and providing examples to help you grasp this essential concept.

## Summary
In this tutorial, we will delve into various components of regex and explain how they work. We will use the regex pattern /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/ to illustrate each component's functionality. By the end of this tutorial, you will have a solid understanding of how regex patterns can be applied to tasks like email validation.


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

### Quantifiers
Quantifiers, like + and {2,6}, determine the number of times a character or group should appear. For example, + means "one or more," and {2,6} means "between 2 and 6" times.

### OR Operator
The | symbol functions as an OR operator, allowing you to specify alternative patterns. For instance, a|b matches either "a" or "b."

### Character Classes
Character classes, enclosed in square brackets, define a set of characters to match. For example, [a-z] matches any lowercase letter.

### Flags
Flags, such as "i" for case-insensitive matching, can be added after the closing delimiter to modify how the regex is applied.

### Grouping and Capturing
Parentheses ( ) are used for grouping and capturing. They help you extract specific parts of the matched text.

### Bracket Expressions
Bracket expressions, like [0-9], define character ranges for matching. They are useful for matching digits, letters, and more.

### Greedy and Lazy Match
Quantifiers are greedy by default, matching as much as possible. Adding ? after a quantifier makes it lazy, matching as little as possible.

### Boundaries
Boundary assertions, such as \b, define word boundaries. They help in finding whole words in text.

### Back-references
Back-references, created with \1, allow you to refer back to captured groups within the regex.

### Look-ahead and Look-behind
Look-ahead (?= ... ) and look-behind (?<= ... ) assertions let you check for patterns ahead or behind the current position without consuming the text.

### Author
This tutorial was created by Nathan Farquhar-Kay. You can connect with the Nathan on https://github.com/nathankay89. If you have any questions or need further clarification, feel free to reach out.

## Gist URL

https://gist.github.com/nathankay89/1ff49c2b277457c84a20518ec08e2717
