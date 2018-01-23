# dataweave1katas
https://docs.mulesoft.com/mule-user-guide/v/3.9/dataweave-operators

## Exercise 1
say Hello, World!

## Excercise 2
Given the src/test/resources/input/exercise2-in.json, produce output as xml that capitalizes the first and last name. Also, make the state abreviation all upper case. 

See src/test/resources/output/exercise2-out.xml for expected output.

## Exercise 3
Given the src/test/resources/input/national_championship.xml, produce output as json that is a list of all id's and first and last name concatinated together. 

See src/test/resources/output/exercise3-out.json for expected output.

## Exercise 4

Given the src/test/resources/input/national_championship.xml, produce output as json that is a list of id's and distance traveled. Order by shortest to farthest distance traveled. 

See src/test/resources/output/exercise4-out.json for expected output.

## Exercise 5

Given the src/test/resources/input/national_championship.xml, produce output as json that contains the following metrics:

* totalAge - Summed total age of all attendees
* avgAgeInt - Average age of all attendees as an Integer
* avgAgeFloat - Average age of all attendees as a Float to nearest tenth
* oldest - age of the oldest attendee
* youngest - age of the youngest attendee

See src/test/resources/output/exercise5-out.json for expected output.

## Exercise 6

Given the src/test/resources/input/national_championship.xml, reorder output by team, last name, and first name.

See src/test/resources/output/exercise6-out.json for expected output.

## Exercise 7

Given the src/test/resources/input/national_championship.xml, produce output as json that groups fans of the same team together, then sorts by the fans by last name, then first name.

See src/test/resources/output/exercise7-out.json for expected output.

## Exercise 8

Given the src/test/resources/input/list_of_states.json, produce output as json that removes all directional states (States that start with North, South, East, or West) from the list.

See src/test/resources/output/exercise8-out.json for expected output.

## Exercise 9

Given the src/test/resources/input/list_of_states.json:
* Make the flowVariable abbrToName contain json that maps the abbreviation to the state name. 
* Make the flowVariable nameToAbbr contain json that maps the state name to the abbreviation.
* Do not change the payload.

See src/test/resources/output/exercise9-abbr-to-name-out.json for abbrToName flowVars expected output and src/test/resources/output/exercise9-name-to-abbr-out.json for nameToAbbr flowVars expected output.

## Exercise 10

Given the src/test/resources/input/list_of_states.json, produce output as json that contains:
* abbreviation - All state abbreviations combined together in a comma seperated string.
* names - All state names combined together in a comma seperated string.

See src/test/resources/output/exercise10-out.json for expected output.

## Exercise 11

Given src/test/resources/input/list_of_states_dupes.json, remove duplicates and order the results in reverse alphabetical order.

See src/test/resources/output/exercise11-out.json for expected output.

## Exercise 12

Given src/test/resources/input/potential_anograms.json produce json that contains:
* allPalindromes - true or false, identifies if all items in the list are palindromes (same forward or backwards)
* palindromes - comma seperated string of all palindromes
* containsNumericPalindromes - true or false, identifies if at least one list entry is a palindrome and is also contains only numerical values
* numericPalindromes - pipe, |, seperated string of all palindromes

See src/test/resources/output/exercise12-out.json for expected output.

## Exercise 13

Recreate FizzBuzz, https://en.wikipedia.org/wiki/Fizz_buzz, with dataweave. The output will be a json object where the key is the number, and the value is either the number, Fizz, Buzz, or Fizz Buzz:
{
	"1": "1",
	"2": "2",
	"3": "Fizz",
	....
}

See src/test/resources/output/exercise13-out.json for expected output.

## Exercise 14

Take the results of FizzBuzz (Exercise 13) and create two lists, one that is all the odd number entries, and other that is all the even.
{
	"even": [],
	"odd": []
}

See src/test/resources/output/exercise14-out.json for expected output.

## Exercise 15

recombine the results of above into one list Exercise 14

##

Other ideas:
	Hamming
	Trim whitespace (adjust one of the above?)
	date coercion
	flow lookup
	create and and write a csv
	zip array
	split string into an array
