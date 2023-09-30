# HippodromeGame
This Java code implements a text-based horse racing game called "Hippodrome." In this game, a virtual racecourse is created where horses compete for the title of the fastest racer.

Main Classes
Hippodrome
The primary class of the game. It manages the game's logic and contains a list of horses.

Methods:
run(): The main method that starts the game and controls the movement of horses and their display for 100 turns.
move(): A method for moving each horse forward. Horses' movement is randomized based on their speed.
print(): A method for displaying the current state of the race, showing the positions of each horse using dots and their names.
getWinner(): A method that determines the winner of the race by comparing the distances covered by each horse.
printWinner(): A method that displays the name of the winning horse on the screen.

Fields:
horses: A list that holds the participating horses in the race.
Horse
A class representing an individual horse in the race. Each horse has a name, a speed, and a distance it has covered.

Methods:
move(): A method that updates the distance covered by the horse based on its speed and a random factor.
print(): A method that displays the horse's progress in the race by printing dots (.) for the distance covered and the horse's name.

Fields:
name: The name of the horse.
speed: The speed of the horse, influencing how fast it moves.
distance: The distance the horse has covered during the race.

How to Play
Run the application.
The game will simulate a horse race on the virtual racecourse for 100 turns.
After 100 turns, the game will announce the winner, which is the horse that has covered the greatest distance.
