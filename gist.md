# RegexTutorial
The regex expression we will be discussing in this file has to do with matching an email <br> /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/<br>. <br>
(user)@(service provider).(domain name)

## Summary
Regex is short hand term for regular expression. Regex statements are commonly used to gather information from any text by exectuing a search by a specific pattern. This can be extremely useful when looking at large databases of information. <br>


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
<br> /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/<br>
Anchors that are utilized in this expression are the ^ character, indicating the beginning of a string and its counterpart , $ character, which ends the string. <br>

### Quantifiers
<br> /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/<br>
Quantifiers that are utilized in the expression are {2,6} which allows the minimum and maximum number of characters to be returned. <br>

### OR Operator
<br> /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/<br>
The OR operator (|) allows for two result cases. For example if we wanted an email ending in .com or .net (.com | .net) which isnt present in this statement.

### Character Classes
<br> /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/<br>
The character class in this expression is in the second group expression notated with the \d. This allows for the matching of any digit between 0-9. Meaning this is short hand for 0-9. 

### Flags
<br> /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/<br>
There are only six flags in regex statements (i or g or m or s or u or y) and they are optional. 
i makes the search case-insensitive. g looks for all matches. m enables multiline mode. s enables dotail mode. u enables unicode support. Finally y enables sticky mode searching.  

### Grouping and Capturing
<br> /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/<br>
The first grouping and capturing matches the users email. The second grouping and capturing matches the service provider. The third grouping and capturing matches the domain name. 

### Bracket Expressions
<br> /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/<br>
Bracket Expressions
[a-z0-9_\.-] <br>
This first bracket allows the match to return any lower case letter from a-z, any number from 0-9 and the specified characters (_ or . or -). <br>
[\da-z\.-]<br>
This second bracket allows the match to return any lower case letter from a-z and the specified characters (. or -). <br>
[a-z\.]<br>
This third bracket allows the match to return any lower case letter from a-z and the specified character (.). <br>

### Greedy and Lazy Match
<br> /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/<br>
This regex contains a greedy match due to + character and {2,6}.  

### Boundaries
<br> /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/<br>
Typical regex statement boundary characters such as (\b) allows for word matching. For example \bball\b would match red ball but not baseball. None are present in this statement.

### Back-references
<br> /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/<br>
Back references \b()\b which allows to search for repeating text and is not present in this regex statement.

### Look-ahead and Look-behind
<br> /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/<br>
Look-ahead and look-behind are able to match a string of characters either before or after depending on the syntext of how the opperation is written. 
look-ahead(?=u) or (?!u)<br>
look-behind (?<=u) or (?<!u) <br>
None of which are present. 

## Author
I am  a new full stack developer and previously a respiratory therapist. 
Aaron Venema Github profile:
https://github.com/AaronVenema
