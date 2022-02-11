# CSE210-03
Jumper Specification

Tension so thick you can cut it with a knife! Jumper seems like a pretty laid back game until it's not! The rules are simple. The jumper guesses letters, one at a time. If the letter's not in the puzzle, the parachute loses a line. Guessing continues until the puzzle is solved or, well, you know.

#Getting Started
Make sure you have Python 3.8.0 or newer installed and running on your machine. Open a terminal and browse to the project's root folder. Start the program by running the following command.

#python3 jumper 
You can also run the program from an IDE like Visual Studio Code. Start your IDE and open the project folder. Select the main module inside the hunter folder and click the "run" icon.

#Project Structure
The project files and folders are organized as follows:
#
root                    (project root folder)
+-- jumper              (source code for game)
  +-- game              (specific game classes)
    +-- console.py      (Class for displaying)
    +-- director.py     (Class for controlling other classes)
    +-- jumper.py       (Class for the win/lose conditions)
    +-- word.py         (Class for generating random word)
  +-- __init__.py       (python package file)
  +-- __main__.py       (entry point for program)
  +-- wordlist.txt      (text document for random word)
+-- README.md           (general info)
#Required Technologies
Python 3.8.0
#Author
