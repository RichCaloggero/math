# Math

A simple program to show how one might use mathjs (https://mathjs.org).

- run: [](https://RichCaloggero.github.io/math/math.html)
- code: https://raw.githubusercontent.com/RichCaloggero/math/master/math.html

## Accessibility

- type expression and press enter or click
	+ both expression and result copied to output pane
	+ new entries are announced automatically by the screen reader as they are added
	+ checking the "announce only result" checkbox will announce only the result rather than both expression and result
- history
		+ upArrow moves back through history and places item into input field
		+ tabbing back through history announces both input and result; press enter to place input expression into input field
+ clicking on a history entry places the input expression into the input field
+ checking the "announce only result" checkbox will announce only results as you walk the history
- the last result is stored in the variable $_ (dollar underscore)

## Example

- 2 + 2
	+ announces 2 + 2, 4
	+ both 2 + 2 and 4 are now displayed in history
	+ shift+tab announces "2 + 2, 4"
	+ pressing upArrow  puts "2 + 2" back into the input field; pressing enter evaluates it

- derivative("2x+3x", "x")
	+ 5

- simplify("2x + 3x")
	+ 5x
- derivative($_, "x")
	+ 5

