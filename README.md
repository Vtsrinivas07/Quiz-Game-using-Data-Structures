# Quiz Game 
# Features
Warmup Round: Players answer 3 general knowledge questions. To proceed to the Challenge Round, they must answer at least 2 questions correctly.
Challenge Round: Players answer 10 questions, each correct answer earning $100,000. The maximum cash prize is $1,000,000.
Score Management: Displays the highest score, allows resetting the score, and updates the score file.
Help Section: Provides instructions and tips on how to play the game.
Player Interaction: Customizes the experience by asking for the player's name and showing personalized messages based on their performance.

# Files
quiz_game.c: The main source file containing the game logic and user interface.
score.txt: A text file used to store and manage high scores.

# Functions
show_record(): Displays the highest score from score.txt.
reset_score(): Resets the score in score.txt to zero.
help(): Shows game instructions and tips.
edit_score(float score, char plnm[20]): Updates the highest score in score.txt if the current score is higher.

# Usage
Start the Game: Press 'S' from the main menu to start the game.
View High Scores: Press 'V' to view the highest score.
Reset Scores: Press 'R' to reset the score.
Help: Press 'H' for game instructions.
Quit: Press 'Q' to exit the game.

