# Assembly: Endgame

A challenging word-guessing game built with React and Vite. This project was created as part of a Scrimba React course.

![Assembly Endgame Game](https://i.imgur.com/your-screenshot-url.png)

## Description

In "Assembly: Endgame," you must guess a secret word letter by letter before Assembly language takes over the programming world! With each incorrect guess, you lose one of your favorite programming languages. You have 8 chances to save the programming world from Assembly's dominance.

## Features

- **Word Guessing**: Guess letters to reveal a randomly selected word.
- **Programming Language Stakes**: Each wrong guess eliminates a programming language (HTML → CSS → JavaScript → React → TypeScript → Node.js → Python → Ruby).
- **Visual Feedback**: Color-coded keyboard showing correct and incorrect guesses.
- **Win/Lose States**: Special messages and animations for game outcomes.
- **Farewell Messages**: Unique farewell messages when a programming language is eliminated.
- **Confetti Animation**: Celebration animation when you win the game.
- **Accessibility**: Built with a11y features for screen readers.
- **Responsive Design**: Playable on various screen sizes.

## Technologies Used

- React
- Vite
- `clsx` - For conditional class names
- `react-confetti` - For win celebration

## Getting Started

### Prerequisites

- Node.js (v14 or higher recommended)
- npm or yarn

### Installation

1. Clone the repository:
    ```bash
    git clone <repository-url>
    ```
2. Install dependencies:
    ```bash
    npm install
    ```
3. Start the development server:
    ```bash
    npm run dev
    ```
4. Open your browser and navigate to [http://localhost:5173](http://localhost:5173).

### Building for Production

Run the following command to build the project:
```bash
npm run build
```
The built files will be in the `dist` directory.

## How to Play

1. The game selects a random English word.
2. Click on letters on the on-screen keyboard to guess.
3. Correct guesses reveal the letter in the word.
4. Incorrect guesses eliminate a programming language.
5. Win by guessing the entire word before losing all 8 programming languages.
6. If you lose, Assembly takes over!

## Credits

- Original project from Scrimba's React Course.
- Word list sourced from common English words.
- Developed as a learning exercise.
- Special thanks to [Scrimba](https://scrimba.com) for the tutorial and inspiration for this project.

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.