
# 📘 Assignment: Games in Python

## 🎯 Objective

Learn to build interactive games using Python by creating a Hangman game that uses strings, loops, conditionals, and user input.

## 📝 Tasks

### 🛠️ Set Up Game Structure

#### Description
Create the basic structure for a Hangman game, including word selection and progress tracking.

#### Requirements
Completed program should:

- Define a list of words to choose from
- Randomly select a word to guess
- Initialize game state variables (attempts remaining, letters guessed, current word display)
- Display the initial game state with underscores (e.g., `_ _ _ _`) representing unknown letters


### 🛠️ Implement Game Loop and Guess Handling

#### Description
Build the main game loop where players can guess letters and see the game state update.

#### Requirements
Completed program should:

- Accept letter guesses from the player
- Check if the guessed letter is in the word
- Update the display to show correctly guessed letters
- Track incorrect guesses and decrease attempts remaining
- Display the current game state after each guess (word progress, attempts left, letters guessed)
- Continue the game until the word is guessed or attempts are exhausted


### 🛠️ Add Win/Lose Conditions

#### Description
Complete the game by implementing win and lose conditions with appropriate messages.

#### Requirements
Completed program should:

- Display a win message when the player correctly guesses the entire word
- Display a lose message when the player runs out of attempts
- Show the final word if the player loses
- Offer the option to play again
