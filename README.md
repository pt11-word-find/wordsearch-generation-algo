# wordsearch-generation-algo

This package contains one default export, a function that takes four parameters: (wordlist, width, height, difficulty)

wordlist - an array of words to be placed in the word search
width / height - integers that indicate the size of the puzzle.
difficulty - An integer. if greater than 1, will include reversed words.

## Helper funcs:

In the "utils" folder, you'll find some helper functions that I found useful in implementing this generator on a react frontend:

arrayIncluded.js - takes 2 arrays, returns true if the second array occurs as an element in the first.

ArraysEqual.js - takes 2 arrays, tests their equivalency. (js does not support `===` equality for arrays)

inLine.js - Takes 3 parameters - an array of selected tiles' coordinates, a new tile's coordinates, and the puzzle itself (for length reference). Returns true if a new selection is in a valid line in the word find


### Disclaimer

This has been minimally tested! Please report any issues or errors on the gh issue tracker or on Twitter @michaelharms70

THIS CAN BE SIMPLIFIED but it works and it's dynamic in sizing