# Regex Tutorial

The purpose of this tutorial is to walk you through what regular expressions are, and how we can use them.

## Summary

 A regular expression is a string of text that lets you create patterns that help match, locate, and manage text. This is great for not only pulling out information from a given body of code, but can also be used for validation. Today’s tutorial will review an example code snippet that we can use to match an email address.


## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Character Escapes](#character-escapes)

## Regex Components
Here is an example code snippet we can use to match emails. A great use for this code can be to validate if an email follows the correct format.


/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

### Anchors
At the beginning and end of searches we have anchors. These check if a string fully matches a pattern despite themselves not matching characters. Anchors create parameters and affirm a string matches a location.

In our example the ^ anchor is there to match the beginning of the text, and the $ anchor is there to match the end of the text.


### Quantifiers
A quantifier measures and sets the limit on the number of characters we want to match in our regular expression. In our example the + matches the pattern oneor more times, and the { n,x } Matches the pattern from a minimum of n number  of times to a maximum of x number of times.

### Grouping Constructs

The () is a way to group a section of Regex. what we put inside the () is called a sub-expression. Capturing groups matches the match character sequence and can be used for possible reuse.

### Bracket Expressions
In our expression this would our brackets []. anything inside these brackets will represent a range of characters that we want to match. for example [a-z] includes all lowercase letters a-z [0-9] includes all numbers 0-9, and then [_-] includes both an _ and a -.
### Character Classes
This defines a set of characters.

. finds a single character, a newline or line terminator is an exceptions

/d finds a digit

## Author

Kyle Gran

https://github.com/Kgran12
