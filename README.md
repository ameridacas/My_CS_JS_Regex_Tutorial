# My_CS_JS_Regex_Tutorial

# Computer Science for JavaScript: Regex Tutorial

Introductory paragraph (replace this with your text)
Welcome to the Regex Mastery Tutorial! In this tutorial, we'll explore the art of regular expressions (regex) with a focus on validating email addresses. Whether you're a beginner or seeking to enhance your skills, this tutorial will guide you through the essential components of a robust email validation regex.

## Summary

There are multiple different ways to use regex expressions to work together to define a specific search pattern. Regex expressions can validate, extract, substitute and modify different classes or elements The remaining sections will go over different types and examples of regex. 


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

Regex Components are composed of anchors, character classes, quantifiers and alternations which are used to define a search pattern.

### Anchors

Anchors are used in regular expressions like /^ which specify the position inside the input where a match must happen.

/^

### Quantifiers

Quantifiers specify the quantity of the preceding element or element before the Zero or More (*) in a regex pattern. The * quantifier matches zero or more occurrences of the preceding element.

/\d*/

### Grouping Constructs

Grouping constructs allow you to treat multiple characters as a single unit or one piece like a Capturing Group ( ) . The parathesis in a capturing group ( ) are used to capture a part of the match. 

/(\d{2})-(\d{2})/

### Bracket Expressions

A Bracket expression is an expression that matches any one of the enclosed characters. An Example of this are Range [ ]. This expression range [ ] specifies a range of characters.

/[a-z]/

### Character Classes

Character classes match any one of the characters within the class.
An example of this is a Word Character \w which is a character class that matches any word character.

/\w+/

### The OR Operator

The OR operator | matches either the pattern on its left or the pattern on its right. An visual example is /(cat|dog)/ which shows the pattern matching from the opposite side. 

### Flags

Flags are used to modify the behavior of the regex pattern.
For example, the (i) is Case Insensitive so the i flag makes a pattern case-insensitive.

/cat/i

### Character Escapes

Character escapes allow you to use special characters as literals.

Escape Special Character (\ ) is an example of this which the symbol
"\" escape allows you to use special characters as literals.

/\$/ 

## Author

Hello, this tutorial was created by Alex Castillo, who is a new upcoming developor learning and interested in finding new wways to code and work with others. Feel free to reach me at "https://github.com/ameridacas".

Github-Deploy="https://ameridacas.github.io/My_CS_JS_Regex_Tutorial/"

Github-Repo="https://github.com/ameridacas/My_CS_JS_Regex_Tutorial/"