## How is Hangman played IRL?

1. Draw the starting point
2. Pick a word
3. Draw dashes -> 1 dash for each letter in the word
    a. For loop?
4. Guessing time
    a. Give an input -. letter
    b. Check if the letter is in the string
        a. If its in the string, replace dash with the letter
        b. If not in the string, draw the next step
        c. No matter, kepp track of guesses user did
            a. Dont let same guess more than once
5. Game ends
    a. If they guess the whole word-> game ends-> you win
    b. If the full body drawn_> game ends-> you lose