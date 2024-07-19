                                   /*OVERVIEW OF THE NUMBER GUESSING GAME*/
 
 A number guessing game in C++ typically involves the computer generating a random number, which the player then tries to guess. Here’s a basic overview of how you might implement such a game

#Explanation:
- **Random Number Generation:** `rand() % 100 + 1` generates a number between 1 and 100.
- **Loop:** The `while` loop continues until `guessed` becomes `true`, indicating the correct guess.
- **Input Handling:** Uses `std::cin` to get input from the player.
- **Conditional Statements:** Checks if the guess is too high, too low, or correct.

# Improvements:
- **Error Handling:** Add input validation to handle non-numeric inputs or out-of-range guesses.
- **Multiple Rounds:** Allow the game to restart automatically or manually after a win.
- **Difficulty Levels:** Modify the range of numbers based on difficulty levels.

This should give you a solid foundation to create a simple number guessing game in C++.
