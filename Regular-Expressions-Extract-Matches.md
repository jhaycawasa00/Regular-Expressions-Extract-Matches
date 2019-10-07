
# Description

Regular Expressions: Extract Matches
So far, you have only been checking if a pattern exists or not within a string. You can also extract the actual matches you found with the .match()method.

To use the .match()method, apply the method on a string and pass in the regex inside the parentheses. Here's an example:

"Hello, World!".match(/Hello/);
// Returns ["Hello"]
let ourStr = "Regular expressions";
let ourRegex = /expressions/;
ourStr.match(ourRegex);
// Returns ["expressions"]


# Instruction

Apply the .match()method to extract the word coding.


# Tests

The resultshould have the word coding
Your regex codingRegexshould search for coding
You should use the .match()method.

# Challenge seed

let extractStr = "Extract the word 'coding' from this string.";

let codingRegex = /change/; // Change this line

let result = extractStr; // Change this line



# Solution

let extractStr = "Extract the word 'coding' from this string.";

let codingRegex = /coding/; // Change this line

let result = extractStr.match(codingRegex) // Change this line
