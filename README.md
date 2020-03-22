# wordsearch-generation-algo

This package contains one default export, a function that takes three parameters: (wordlist, width, height)

wordlist - an array of words to be placed in the word search
width / height - integers that indicate the size of the puzzle.

## Planned improvements

- Difficulty - allow a parameter to be passed into the generator to specify difficulty - this will limit the word directions (remove reversed diagonals, remove backwards words)

- Forced Variety - Because of the nature of the current looping, the algorithm disfavors diagonal words and they are rarer than they should be.

THIS CAN BE SIMPLIFIED but it works and it's dynamic in sizing