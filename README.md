# Hangman_Game

The Hangman Game is a Java Swing-based application that delivers an interactive and
visually engaging gaming experience. Within the main frame governed by JFrame,
players can seamlessly input their names, initiate the game, and embark on the challenge
of guessing a randomly selected word by entering single-letter guesses. The initial size of
the frame is set to a user-friendly 600x400 pixels, ensuring an aesthetically pleasing
display.
The user interface features a JTextField for players to input their names and a "Start
Game" button that triggers the initiation of the game. A notable aspect of the UI is its
adaptability, dynamically adjusting its components to provide a responsive and
user-friendly experience, particularly when the frame is resized.
The core game logic involves the random selection of a word from a predefined list, its
representation through lines corresponding to each letter, and the facilitation of player
guesses via a JTextField and associated "Guess" button. The system effectively tracks
incorrect guesses, updating a custom HangmanPanel to visually represent the hangman
figure based on the number of incorrect attempts.
The HangmanPanel, implemented as a custom JPanel class, serves as a crucial component
for visualizing the hangman figure. This dynamic panel provides a visual progression,
illustrating the head, body, and limbs of the hangman as incorrect guesses accumulate
during gameplay.
End-game handling is robustly implemented to notify players of their game outcome,
whether it be successful word completion or the exhaustion of eight incorrect attempts.
The system offers a seamless transition for players to start a new game, maintaining the
overall fluidity and user-friendliness of the gaming experience.
