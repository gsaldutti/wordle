# WordleSolver

For educational purposes, a simple script that assists in solving the word game [Wordle](https://www.powerlanguage.co.uk/wordle/).

## Instructions

1. Pick your first word from the suggested words list or come up with your own word.
2. In the "Filtering out the top words." replace the string variable with the word you picked.
3. Update the Val enum values with the corresponding index of your word.
   - exactly: the letter is found in the word and in the correct spot.
   - exist: the letter is in the word but in the wrong spot.
   - nonexistent: the letter is not found in the word.

    ### Example
    ![First Word](images/first_word.png)

        word = 'media'
        validations = [Val.exactly, Val.nonexistent, Val.nonexistent, Val.exist, Val.nonexistent]

    - The first letter in my word is green so I will update the first item in the validations list to "Val.exactly"
    - The second letter is not found in the word so we change the second item in the validations list to "Val.nonexistent"
    - The fourth letter is found in the word but not in the correct spot so we change the fourth item in the validations list to "Val.exist"

4. Run the cell to generate a new list of words.
5. Repeat till you solve the word of the day.

Contributed by: Gregg R. Saldutti

Email: greggnyc1@gmail.com

[![Linkedin](https://i.stack.imgur.com/gVE0j.png) LinkedIn](https://www.linkedin.com/in/greggsaldutti-1701501)


---

## License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


Contributors

Contributed by: Gregg R. Saldutti

Email: greggnyc1@gmail.com

[![Linkedin](https://i.stack.imgur.com/gVE0j.png) LinkedIn](https://www.linkedin.com/in/greggsaldutti-1701501)



Copyright © 2022 #Password


Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
