# Number Guessing Game

A simple C++ console game where the player tries to guess a randomly generated number between 1 and 100. The game offers three difficulty levels: Easy, Medium, and Hard, each with a different number of chances.

## Project URL
https://github.com/kalash260203/Number-Guessing-Game

<p align="center">
  <img width="528" height="451" alt="image" src="https://github.com/user-attachments/assets/3ebf7b73-a9b4-4480-af52-2e1ec157b511" />
</p>

## Features
- Random number generation
- Three difficulty levels
- Input validation
- Feedback on guesses

## How to Play
1. Run the program.
2. Select a difficulty level:
   - Easy: 10 chances
   - Medium: 5 chances
   - Hard: 3 chances
3. Enter your guesses. The program will tell you if your guess is too high or too low.
4. Try to guess the correct number within the allowed chances.

## How It Works
- The program generates a random number between 1 and 100.
- You select a difficulty level, which sets the number of guesses allowed.
- For each guess, the program checks if your input is valid and provides feedback.
- If you guess correctly, you win. Otherwise, the correct number is revealed after all chances are used.

## Code Overview
- `generateRandomNumber()`: Generates a random number between 1 and 100.
- `main()`: Handles game logic, user input, and output.

## Requirements
- C++ compiler (e.g., g++)
