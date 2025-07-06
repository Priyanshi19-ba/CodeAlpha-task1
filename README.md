# CodeAlpha-task1
**Name: Priyanshi Bansal**
Company:CodeAlpha 
Student ID: CA/JU1/14308
Duration: 10 June 2025 to 10 July 2025
Domain : Python Programmig 
Overview of the project
**Project: Hangman Game – A Text-Based Word Guessing Game in Python**

**Objective**:The objective of this project is to create a simple text-based Hangman game where the player guesses a hidden word one letter at a time. The game uses a small list of 5 predefined words, and the player is allowed a maximum of 6 incorrect guesses. This project is designed to help practice and apply basic programming concepts such as random selection, while loops, if-else statements, strings, and lists.

**Key Activities:**
1.Importing Required Module
The random module is imported to randomly select a word from the list.
2.Defining the Word List
A predefined list of five words (word_list) is created for the game.
3.Selecting the Secret Word
The program randomly selects one word from the list as the secret word using random.choice().
4.Initializing Game State Variables
guessed_letters: An empty list to keep track of all letters guessed by the player.
incorrect_guesses: A counter to track the number of incorrect guesses made.
max_incorrect: The maximum number of incorrect guesses allowed (set to 6).
display_word: A list representing the current state of the guessed word, initially filled with underscores.
5.Displaying Game Instructions
The program prints a welcome message and basic instructions for the player.
6.Main Game Loop
The game runs in a while loop that continues as long as the player has not exceeded the maximum number of incorrect guesses and the word is not fully guessed.
7.Displaying the Current Word State
The current state of the word (with guessed letters and underscores) is shown to the player each round.
8.Taking User Input
The player is prompted to enter a letter as their guess.
9.Input Validation
The code checks if the input is a single alphabet letter.
If not, it asks the player to enter a valid letter.
10.Checking for Repeated Guesses
The code checks if the player has already guessed the letter before.
11.Updating Guessed Letters
The guessed letter is added to the guessed_letters list.
12.Checking the Guess
If the guessed letter is in the secret word:
The program updates display_word to reveal all positions of that letter.
A message is shown for a correct guess.
If the guessed letter is not in the word:
The incorrect_guesses counter is increased.
The player is informed of the remaining guesses.
13.Ending the Game
If the player successfully guesses all letters, a congratulatory message is displayed.
If the player runs out of guesses, the correct word is revealed and the game ends.

**Technologies Used:**
1.Python Programming Language:
The entire game is implemented using Python, which is a popular, high-level programming language suitable for beginners and widely used for scripting and small projects.
2.Python Standard Library (random module):
The random module is used to randomly select a word from the predefined list, making each game unique.
3.Console Input/Output:
The game interacts with the player using basic console input (input()) and output (print()), allowing the player to enter guesses and see game messages.
4.Core Programming Concepts:
Variables and Lists: Used to store the word list, guessed letters, and the current display state of the word.
Loops (while loop): Controls the main game flow, repeating until the game ends.
Conditional Statements (if-else): Used for input validation, checking guesses, and determining win/loss conditions.
String Manipulation: For updating and displaying the guessed word and processing user input.
No external libraries, files, or graphical/audio technologies are used—everything relies on Python’s built-in features and the command-line interface.

**Key Insights:**
1.Word Guessing and Deduction:
The game is fundamentally about guessing a hidden word, one letter at a time, using logic and deduction. Players must use their reasoning skills to make educated guesses based on previously revealed letters and the structure of the word.
2.Limited Attempts:
Players have a fixed number of incorrect guesses (in your code, 6). This limitation adds challenge and urgency, making each guess important.
3.State Tracking:
The program keeps track of:
The secret word.
Letters already guessed.
The number of incorrect guesses.
The current state of the word (with correct guesses revealed and the rest hidden).
4.Input Validation and User Feedback:
The game validates user input to ensure only single alphabetic characters are accepted and prevents repeated guesses, providing clear feedback for invalid or duplicate entries.
5.Progressive Reveal:
Correct guesses reveal all instances of that letter in the word, while incorrect guesses reduce the remaining attempts. The display updates after each guess to show progress.
6.Win/Loss Conditions:
The game ends when the player either successfully guesses the entire word or uses up all allowed incorrect guesses. The outcome is clearly communicated to the player.
7.Simple Console-Based Interaction:
The game uses basic console input/output, making it accessible and easy to play without graphical requirements.
