---
nam: your name here 
semester: spring 24
course: cis106
---

# Week Report 6

## Wildcards.


### * Wildcard
the * wilcard matches from 0 to any number of characters.
*Example:
 *List all the text file in a directory 
 * `ls file`*
* List all the files that start with the word file 
 *  `ls file`*
* Copy all the mp4 files
*  `cp Downloads/*.mp ~/Videos/Movies/`
![wilcard](wilcard00.png)

## ? Wildcard 
The wildcard matches a single caracter
 * Example
  * List all the files that have 3 characters and are 
  followed by the words files in the name 
![wilcard](wilcard..png)

## [ ] wildcard
 * The brackets wilcard math a single chacacter in a renge
 * the brackets wilcard use the exclamation mark to reverse to reverse the match.
 * For example 
 * Ls f[aeiou]*  ls E[cars!]* , ls [computer-]* ls *[0-55]**
![wilcard](wilcard..png)

## brace Expansion 
 * brace expasion {} is not a wilcard but another feature of bash that allows you to generate arbitrary stringst to use with commands.also Brace expansion and wildcard characters can be combined in Linux to generate a list of filenames or other strings based on patterns.
 * For exmaple file{1..3}.txt file{1..3}. file{A..z},js
 ![wilcard](wilcard4..png)