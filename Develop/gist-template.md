# Regex Tutorial

This tutorial is going to explain the use of regex to match emails using the expression /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/. This is useful when validating emails using web applications and technologies.

## Summary

Regex is a sequence of characters that specifies a search pattern in text. Usually such patterns are used by string-searching algorithms for "find" or "find and replace" operations on strings, or for input validation. Regular expression techniques are developed in theoretical computer science and formal language theory. This tutorial will go over the components of a regex and how it applies to matching an email.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
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

The caret anchor ^ signafies the beginning of the text. $ is the dollar achor that matches the end of the text.

### Quantifiers

{2,6} are our quantifiers for this regex. When you append it to a character or character class, it specifies how many characters or character classes you want to match. The + operator, which will connect the users email name + email service + .com. 


### Character Classes

A character class is a special notation that matches any symbol from a certain set. The character class in this expression is \d, which matches a single characters that is a digit from 0-9.

### Flags

A flag changes the default searching behavior of a regular expression. It makes a regex search in a different way. 

### Grouping and Capturing

The capturing groups in this are ([a-z0-9_\.-]+), ([\da-z\.-]+), and ([a-z\.]{2,6}). It allows to get a part of the match as a separate item in the result array. ([a-z0-9_\.-]+) that matches the user email name. The second capturing group is ([\da-z\.-]+) which will match the email service. Then lastly, capture group #3 is ([a-z\.]{2,6}) to capture the website domain.

### Bracket Expressions

A bracket expression is a list of characters enclosed by ‘[’ and ‘]’. The expressions in this regex are [a-z\.] which matches any character a-z(case senstive) and the character ". [\da-z\.-], which is matching a single digit from 0-9, any character a-z (case senstive), and the characters "." and "-".; ". And a-z0-9_\.-], which is matching any letter a-z and is case senstive. It also matches a character 0-9 and matches the characters "_" , "-" , and ".".


 
### Greedy and Lazy Match



### Boundaries



### Back-references



### Look-ahead and Look-behind



## Author

- [@Douglas Snodgrass](https://www.github.com/purplepenguin67)

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
