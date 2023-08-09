**# Hangman Python Game**

This is a simple implementation of the classic Hangman game in Python. The game randomly selects a word from a predefined list and the player's objective is to guess the letters in the word within a certain number of attempts.

**Features**
Randomly selects a word for each game from a predefined list.
Displays the current state of the hangman as the player makes incorrect guesses.
Tracks and displays the letters guessed by the player.
Provides feedback on the guessed letters and updates the word's display as correct letters are guessed.
Ends the game when the player correctly guesses the word or runs out of attempts.

**How to Play**
Run the script using a Python interpreter.
The game will display a series of underscores representing the letters in the selected word. You will also see an initial state of the hangman.
Guess a letter by typing it on the keyboard and pressing Enter.
The game will provide feedback on whether the letter is correct or incorrect. If it's correct, the letter will replace the corresponding underscore(s). If it's incorrect, the hangman will progress towards completion.
Continue guessing letters one by one until you either guess the entire word (win) or the hangman is completed (lose).

**Files**
main.py: The main game script.
hangman_words.py: Contains the predefined list of words for the game.
hangman_art.py: Contains the stages interface and logo of the game.

**Requirements**
Python 3.x

**Getting Started**
Clone or download the repository to your local machine.
Make sure you have Python 3.x installed.
Open a terminal or command prompt and navigate to the project directory.
Run the command: python main.py
Customization
You can customize the game by modifying the hangman_words.py file to include your own list of words. You can also adjust the number of allowed incorrect guesses by changing the value of the MAX_INCORRECT_GUESSES variable in the main.py file.

Credits
This Hangman game was created by me(Anshika Soni). You can find the original source code and more projects on GitHub.

Enjoy the game! If you have any questions or suggestions, feel free to contact me at [anshikasoni357@gmail.com].

