# Regex Tutorial 

A walkthrough/tutorial of the regex expression in javascript!

# Summary

A regex expression is a sequence of characters that defines or is a search pattern. 

The regex I will be using is the /^#?([a-f0-9]{6}|[a-f0-9]{3})$/ regex used for finding hex values.



## Regex Components


Literal characters: means--you literally want to search for that character

Meta characters: characters that (can) have different values


### Anchor

The anchor: ^

code: /^#

this ensures the string will start with a hashtag '#'


### Quantifiers

The quantifier: ?

code: /^#?

makes the character optional, in this case it makes the character preceding the regex optional, the '#'

### OR Operator

The OR operator: |

code: [a-f0-9]{6}|[a-f0-9]{3}

searches for either the first expression or second expression to be true in the found code snippet.

in our case we will find either a 6 character string with a-f or 0-9 OR a three character string with a combination of a-f or 0-9


## Author

Hi, my name is Troy Nelson. My github is: github.com/troymnelson
Contact me through my email for any questions: troymnlsn@gmail.com

