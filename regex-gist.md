# Date Regex

The regular expression i will be explaining is an expression that can be used to verify the date. It can be used to verify the different ways the date can be written, as long as the pattern follows a two digit day, two digit month and a four digit year.

## Summary
(\d{2}).(\d{2}).(\d{4})
It can be used to verify the different ways the date can be written, as long as the pattern follows a two digit day, two digit month and a four digit year. As you can see the regular expression is divided in parenthesis. this is to distinguish the groups from each other. in the first parenthesis, the back slash followed by the letter d, mean any number from 0-9. when they are followed by the number two in brackets, it will look for any pattern that begins with a two digit number each of which can be between 0-9.
The "." that follows the first group means it is looking for a pattern that fufills the first group followed by any special character, whether it be a space, slash, dash or a period. the second group is looking for the same thing as the first group, followed by the ".". and the third group is looking for four numbers from 0-9 grouped together. 

## Table of Contents

- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)

## Regex Components

### Quantifiers  
the curly brackets were used as quatifiers to limit the amout of numbers are allowed in each group.
### Character Classes
The digit character class was used, which is the /d to distinguish a single character digit from 0-9.
The "." character class was also used to look for groups that were separated by a special character.

### Grouping and Capturing
grouping was used to determine the groups of numbers and how many numbers we are looking for.
## Author
link to github:
https://github.com/ascosper/Date-Regex 