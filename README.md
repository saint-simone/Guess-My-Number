# Number Guessing Game

A simple and interactive number guessing game built with HTML, CSS & JavaScript where players try to guess a randomly generated number between 1 and 20.

## 🎮 Game Features

- Random number generation between 1-20
- Score tracking system (starting at 20)
- High score functionality
- Visual feedback for correct/incorrect guesses
- Responsive messages for game interaction
- "Play Again" functionality

## 🎯 How to Play

1. The game generates a random number between 1 and 20
2. Enter your guess in the input field
3. Click the "Check!" button to submit your guess
4. The game will provide feedback:
   - "📈 Too high!" if your guess is above the secret number
   - "📉 Too low!" if your guess is below the secret number
   - "🎉 Correct Number!" if you guess correctly
5. Each incorrect guess reduces your score by 1
6. Try to guess the number before running out of points!

## 🏆 Scoring System

- You start with 20 points
- Each wrong guess deducts 1 point
- The game tracks your highest score
- If you reach 0 points, you lose the game

## 🔄 Game Controls

- **Check Button**: Validates your guess
- **Again Button**: Resets the game while preserving the high score
- **Input Field**: Enter your number guess (1-20)

## 🎨 Visual Features

- Background color changes to green when you win
- The correct number is revealed upon winning
- The number display box size increases when you win
- Clean and intuitive user interface

## 💻 Technical Implementation

The game is built using:
- JavaScript, HTML, and CSS for the game logic and UI
- DOM manipulation
- Event listeners
- Conditional logic for game rules
- CSS for visual feedback

## 🚀 Future Improvements

Potential enhancements could include:
- Difficulty levels with different ranges
- Time-based scoring
- Sound effects
- Multiplayer functionality
- Mobile-responsive design
