# Word-Guessing-Game
A word guessing game that is 100% right all the time

## How it works:

Suppose the work we have in mind is __'cat'__ .
The program will ask us `How many letters are there in your word? : `
We enter __3__ . The output on the program will look something like:
`[['a', 'b', 'c'], ['d', 'e', 'f'], ['g', 'h', 'i'], ['j', 'k', 'l'], ['m', 'n', 'o'], ['p', 'q', 'r'], ['s', 't', 'u'], ['v', 'w', 'x'], ['y', 'z']]
Which group is the letter 1 of your guess (count starts from 1): `

Since __c__ in in the first group, we enter __1__
The output of the program will be:
`Which group is the letter 2 of your guess (count starts from 1): `
We enter __1__ again. Then it will ask us for our 3rd group and put __7__.
Now, the program should print out the following lines:
`a | b | c

a | b | c

s | t | u

Which column is the letter 1 of your guess (count starts from 1): `

We enter __3__ as __c__ in in the 3rd column. It will ask us for our second column, we input __1__.
It will finally ask for our 3rd column, we input __2__.

Then the program should print out:

`The word you guessed is cat !`

There you go, a simple word 'guessing' game implemented in python with an accuracy rate of 100%.

### Fork it, Share it, improve it and have fun with it!
