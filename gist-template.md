GIVEN a regex tutorial
WHEN I open the tutorial
THEN I see a descriptive title and introductory paragraph explaining the purpose of the tutorial, a summary describing the regex featured in the tutorial, a table of contents linking to different sections that break down each component of the regex and explain what it does, and a section about the author with a link to the author’s GitHub profile
WHEN I click on the links in the table of contents
THEN I am taken to the corresponding sections of the tutorial
WHEN I read through each section of the tutorial
THEN I find a detailed explanation of what a specific component of the regex does
WHEN I reach the end of the tutorial
THEN I find a section about the author and a link to the author’s GitHub profile


# Title (replace with your title)

In this tutorial, we will be going over Regex or regular expressions. We will go over what they are and how they work. 

## Summary

A Regex or regular expression is a sequence of characters that defines a specific search pattern. Regular expressions can be used to find certain patterns of characters within a string, or to find and replace a character or sequence within a string. 

We will be going over matching emails. This regex will be used to validate that an email follows the correct format.

Matching an Email:
```
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/
```

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
```
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/
```
In the above example of the email regex you will see ^ and $. 

These two are called anchors. 

The ^ anchor signifies the beginning of our string.

The $ anchor signifies the end of our string. 

In between these two anchors is the code we are using to make sure the user is inputing the valid format for their email.


### Quantifiers

Quantifiers are charcters in the regex that specifiy how many times a character, group, or class must be represented in the users input to be matched.

```
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/
```

In the above example we can see ([a-z0-9_\.-]+) is stating that the user can use any letter a-z and any number 0-9 and the following characters _, \, ., -. The + is a quantifier. This means that the users input must contain at least one mentioned criterias.


### Character Classes

Character classes in a regex defines a set of characters, anyone of which can occur in an input string to fulfill a match.

```
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/
```

In the above example we can see ([\da-z\.-]+)

The \d character matches any Arabic numeral digit. This is the same as [0-9] we saw in the first portion of our regex.

### Flags

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
