# Wordle Game

## Description

This is my first game development project on Python, after learning the basic skills of manipulating lists, arrays and different data types along with
loops and logical statements I used my knowledge to build a python version of the popular wordle game from the New York Times. This project was developed on
jupyter notebook and it aims to mimic the wordle game where you must guess the word while being provided colour hints to aid you (full instructions below).

I used Python to develop this project as it is a programming language I am eager to learn. I began with developing a barebone functional word guessing game
that compared the user input and the word to guess then returned outputs based on a logical series. Then I continually developed the code adding validations,
loops for attempts, letter and letter position comparisons, and random words to guess. 

The most challenging aspect was developing a GUI for a better user experience, although the logic and fucntionality was there I had to learn how to develop
a GUI from scratch. Similarly, I began with a basic user input and button layout, then progressed to make these functional with my original script. Overall,
I am happy with my progress and the basic functionality of the game, there is much work to be done but I have enjoyed playing with my own creation.

Moving forwards, I would like to add more validation on the user inputs, such that they are limited to only inputing real words and also improve the general 
asthetics of the GUI to make it more user friendly and clean.

### Prerequsites

Ensure Python is installed on your local computer, as of 08/03/2024 on a Python 3 kernel this code is operational.

### Installation

The notebooks AbhishekBheekha_04_01_Project_PythonGameDevelopment.ipynb and words.ipynb can be cloned to your local machine and will both be required to run the game. Please ensure AbhishekBheekha_04_01_Project_PythonGameDevelopment.ipynb and words.ipynb are in the same folder.

Included in the code are the relevant libraries and modules to run the game, import-ipynb will need to be installed using '!pip install import-ipynb'.

'import words' imports the function to select a random word from a large list compiled, this will be compulsory to play the game.
# Wordle Game

## Description

This is my first game development project on Python, after learning the basic skills of manipulating lists, arrays and different data types along with
loops and logical statements I used my knowledge to build a python version of the popular wordle game from the New York Times. This project was developed on
jupyter notebook and it aims to mimic the wordle game where you must guess the word while being provided colour hints to aid you (full instructions below).

I used Python to develop this project as it is a programming language I am eager to learn. I began with developing a barebone functional word guessing game
that compared the user input and the word to guess then returned outputs based on a logical series. Then I continually developed the code adding validations,
loops for attempts, letter and letter position comparisons, and random words to guess. 

The most challenging aspect was developing a GUI for a better user experience, although the logic and functionality was there I had to learn how to develop
a GUI from scratch. Similarly, I began with a basic user input and button layout, then progressed to make these functional with my original script. Overall,
I am happy with my progress and the basic functionality of the game, there is much work to be done but I have enjoyed playing with my own creation.

Moving forwards, I would like to add more validation on the user inputs, such that they are limited to only inputting real words and also improve the general 
aesthetics of the GUI to make it more user friendly and clean.

### Prerequsites

Ensure Python is installed on your local computer, as of 08/03/2024 on a Python 3 kernel this code is operational.

### Installation

The notebooks AbhishekBheekha_04_01_Project_PythonGameDevelopment.ipynb and words.ipynb can be cloned to your local machine and will both be required to run the game. Please ensure AbhishekBheekha_04_01_Project_PythonGameDevelopment.ipynb and words.ipynb are in the same folder.

Included in the code are the relevant libraries and modules to run the game, import-ipynb will need to be installed using '!pip install import-ipynb'.

'import words' imports the function to select a random word from a large list compiled, this will be compulsory to play the game.

## GITHUB

https://github.com/AbhishekBheekha/Wordle

GameCode is the main python GUI wordle game, words must be saved as 'words' in the same folder. Both files can be cloned to your local computer.

### How to play

Wordle rules: 

Aim - To guess the four letter word.

Each guess must be a valid four-letter word.

The colour of a tile will change to show you how close your guess was.

If the tile turns green, the letter is in the word, and it is in the correct spot.

If the tile turns yellow, the letter is in the word, but it is not in the correct spot.

If the tile turns grey, the letter is not in the word.

Upon running, a GUI will appear on the top left of your screen with a window with a text entry box, a guess button, and a instructions button. The text entry will be where the user will input their four letter guess, then they can then either press guess or the enter key to submit their first guess. The user will only have five guesses using the rules above to guess the word. 

Whether the user is successful or not in determining the word, they will be asked if they want to play again, if so, the window will reset with a new word for them to guess. The instructions button is readily available at all times if the user forgets the rules. If the user is done playing, they may either press the exit button in the top right corner of the window or choose to not play again after completion.

## Credits

Rockborne: Miguel Angel Sanchez Razo and Bruna Tessaro
New York Time Wordle: (https://www.nytimes.com/games/wordle/index.html)

## License

MIT License

Copyright (c) 2024 Abhishek Bheekha

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

