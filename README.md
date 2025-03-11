## AI Number Guessing Game

## DESCRIPTION

The AI Number Guessing Game is a simple command-line game where the AI attempts to guess the number you are thinking of using the binary search algorithm. The game is interactive, allowing the user to provide feedback on each guess, guiding the AI towards the correct number.

## HOW IT WORKS

The user thinks of a number between 1 and 100.

The AI makes a guess based on the middle value of the current range.

## The user provides feedback:

Enter 'h' if the guessed number is too high.

Enter 'l' if the guessed number is too low.

Enter 'c' if the AI guessed correctly.

The AI adjusts its guessing range based on the feedback.

The game continues until the AI correctly guesses the number.

The AI displays the number of attempts taken to guess correctly.

## FEATURES

Uses binary search for efficient guessing.

Interactive user input for feedback.

Simple and easy-to-use command-line interface.

Includes error handling for invalid inputs.

Small delay added for an improved user experience.

## INSTALLATION

Ensure you have Python installed (Python 3.x recommended).

Download or copy the ai_number_guessing.py file.

## Usage

Run the script in a terminal or command prompt:

python ai_number_guessing.py

Follow the on-screen instructions to play the game.

## Example Interaction

Welcome to the AI Number Guessing Game!
Think of a number between 1 and 100, and I will try to guess it.
Press Enter when you are ready...

AI guesses: 50
Is my guess (h)High, (l)Low, or (c)Correct? l

AI guesses: 75
Is my guess (h)High, (l)Low, or (c)Correct? h

AI guesses: 62
Is my guess (h)High, (l)Low, or (c)Correct? c

Hurray! AI guessed your number 62 correctly in 3 attempts! 🎉



