# Title (replace with your title)

regular expression (Regex) is an simplistic but useful pattern.
It is used for many reasons and is very reliable for credential validation you can use it for passwords emails username, and much more.
it can even help you search for specific characters, letters, numbers, and special characters. there is much to explore when it comes to this top so lets get right into it. 

## Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.

lets go into a scenario that i am setting up a username but unfortunatley it cant go through why is that you ask? its all because of this ^supercooldude$ its a regular expression(regex) it helps preventing any username from being identical but there are more powerful ways to use regex for a methods

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
Regex consist of certain characters that are set in place for many reasons the expression "^supercooldude$" lets break this down here the "^" and "$" these characters in regex is called operator characters they are usaully before and after the expression they hold no signifigance other than that though
### Anchors
anchors are a sequence of characters that matches nothing this can be used to repesent the start and end of the expresion it can use to find a pattern of your choice.you should use anchors at all times as well.
### Quantifiers
quantifiers are used to formulate possible matches to the code you are looking for it is also another very helpful method on tracking your code "*,+,?" all have similar purposes of cbeing used to show show if there are characters present.
### OR Operator
and if you want to make more advanced methods of checking you can use the or operated aka "||" but you most likely familiar with this if you have basic javascript its not that different from how you use it to an extent lets take another look at our code ^i would like a (?:small|Large) drink$
do you notice a difference its because the or operated use only one special character instead of two pay attention to how it gives variety to the customers option when it comes to regular expression  you can also use this to have different choice say if the customer cant get a large drink they have the option to choose a backup beverage the small drink!! so lets take it back to coding the or operater gives you an backup option to chose if anything goes sour
### Character Classes
character classes also known as character sets is a feature that allows you to look for specific characters basically giving the engine a specific search this can be used as a way to look in a big file or module for an example lets you were reading though document you dont remember the word you just know it has a "s" and a "k" lets put those to words in a bracket like this [sk] and now we have found it "asteri[sk]" now were arent lost anymore!
### Flags
flags are not necessary but very useful for altering they way trhe search is conducted flags have many different ways of doing so flags are known to take strings and sort them in a alphabetical order and switch text
there are case sensitive searches and others that match specically to what you need.
### Grouping and Capturing
group and capturing takes a a pattern group in parentheses and finds the most indentical patten within the search and takes it as a wholes so when we put a letters in a parentheses (xyz) it will find a match to this pattern.
### Bracket Expressions
bracket expressions are around the characters that you are trying to match so if i have 'regex'.match(/re/) it will find the first two letters in the word regex is a match
### Greedy and Lazy Match
greedy match is a way of  taking a few words from a quote or string and fixiating on the quoted words and the string between them for example if we look for words that are quoted it wiil match the first quotation mark and the last one '"just "like "this"' this is known as a greedy search 
but a lazy search strictly would take the queeted words as "like","this" it is only ready to use  if a question mark is in quoted.
### Boundaries
Boundaries are anchors that look for words only to match it does not take spaces as well so that means it is zero legnth it should look like this
 b/letters/b
### Back-references
back refrences is a way to capture characters and look for the same characters repeatedly this can be  helpful if you are looking for multiple quotes as well in my personal opinion i find it to be one of the most interesting elements of regex.
### Look-ahead and Look-behind
a look a head is a form of syntax you can use to see if there is any matches in front of your search it will look like this (?=foo) lets breakdown this becasue initally it looks very confusing so this is called a look ahead the "foo" symbolizes the where your match is at so it is telling the search engine where it is and the look behind does the oppisite (?<=foo) you will notice some nuances as you can see the "<" tells the search engine  to look behind the position your match is  
## Author
written by elijah linton currently an amataur web developer 
[https://github.com/ElijahLinton]
