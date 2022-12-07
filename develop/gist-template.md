# Email regex

Come and learn how easy regex( Regular expressions), and how you can you them to your advantage! The regex we will be using in this lession is `/^.+@.+$/`


## Summary
In this walk through we will be learning what a regex also knows and regular expressions are and how we can use them to our advantage. We will break down and a simple to understand regex that will help us find an email fast and efficiantly! There are many ways to write a regex, we decied to pick a simple and short regex that is less imtimidation to breakdown to help you understand the why and how.

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
  The anchors that are found in out regex is `^` which means to start the search at the begining od a string. The `$` signifies the end of the string.
### Quantifiers
  The quantifiers used are `.+` meaning any character 1 or greater in leangth. The `.` single character means any kind of character, the `+` means one or greater. This keeps the regex short and simple. Adding stricter rules can help strengthen the regex and imporve the searcher for example([\w\S\.]) this would insure that the email contains a stringt that has `\S`(no white spaces).
### OR Operator
There is no grouping in our regex but and be seen in the example above. `([\w\S\.])` this groups a string that contains `\w` (any character a-z,A-Z, 0-9) but also makes sure our string doesnt have any white spaces or tabes with `\S`
### Character Classes
  Character Classes can also be seen in our example. the `\w` is an example of a character class that lookes for any character with the value `a-z,A-Z, 0-9`
### Flags
  a regex contains a pattern of optional flags, There are only 6 flags in JavaScript `i,g,m,s,u,y` each had its own unique way of affecting the search. For example the `i` flag makes the search not case-sensitive `A=a`
### Grouping and Capturing
  As seen in our more complicated example `([\w\S\.])`we use `()` which groupes the regular expression within`()`.
### Bracket Expressions
  The `[]` seen in `([\w\S\.])` matches any characters enclosed in the brackets
### Greedy and Lazy Match
  Our regex `/^.+@.+$/` is a lazy regex that can return invalid emails by allowing any type of string `.+` followed by a `@`
  followed by another string greater than 1 `.+` which is greedy and lazy.
### Boundaries
  the example regex `([\w\S\.])` has a boundry in it as well the `\S` the quanifier `\s` looks for white spaces. THe `\S` inclused a uppercase `S` singifiying anything that isnt a white space. 
### Back-references

### Look-ahead and Look-behind
https://javascript.info/regexp-boundary
https://projects.lukehaas.me/regexhub/
https://javascript.info/regexp-introduction
https://www.regextutorial.org/regular-expression-metacharacters.php

## Author
Pablo Ramirez
github: github.com/graslowsnail
email: graslowsnail@gmail.com
