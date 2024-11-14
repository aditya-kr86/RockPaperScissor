# Rock Paper Scissor Game 🎮

Welcome to the **Rock Paper Scissor Game**! A classic game where you can challenge your computer and test your luck.

## Game Description

This is a console-based **Rock, Paper, Scissors** game where you play against the computer. The game is simple:

- **Rock** beats **Scissors**.
- **Paper** beats **Rock**.
- **Scissors** beats **Paper**.

You can play multiple rounds until you decide to exit the game.

## Features

- **Interactive gameplay**: The game keeps running until you choose to exit.
- **ASCII Art**: Each choice comes with cool ASCII art to enhance the gaming experience.
- **Randomized Computer Choice**: The computer randomly selects between Rock, Paper, and Scissors, making it unpredictable.

## How to Play

1. Clone the repository or copy the code into your Python environment.
2. Run the Python script.
3. You will be prompted to choose:
   - Enter **1** for Rock 🪨
   - Enter **2** for Paper 📄
   - Enter **3** for Scissors ✂️
   - Enter **0** to exit the game.

4. The computer will randomly select its choice.
5. The winner is determined based on the standard rules:
   - Rock beats Scissors
   - Paper beats Rock
   - Scissors beats Paper
6. The game announces the winner of each round.
7. Continue playing or exit as you wish.

## Prerequisites

- Python 3.x
- Basic understanding of running Python scripts.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/aditya-kr86/RockPaperScissor.git
   ```

2. **Navigate to the project folder**:
   ```bash
   cd RockPaperScissor
   ```

3. **Run the game**:
   ```bash
   python rock_paper_scissor.py
   ```

## Code Explanation

- The game uses the `random` module to make the computer's choice unpredictable.
- It features a loop that keeps running until the player chooses to exit by entering **0**.
- Player and computer choices are displayed with ASCII art for better visualization.

### Example Gameplay

```
█▀█ █▀█ █▀▀ █▄▀     █▀█ ▄▀█ █▀█ █▀▀ █▀█     █▀ █▀▀ █ █▀ █▀ █▀█ █▀█ █▀
█▀▄ █▄█ █▄▄ █ █     █▀▀ █▀█ █▀▀ ██▄ █▀▄     ▄█ █▄▄ █ ▄█ ▄█ █▄█ █▀▄ ▄█

Enter any-one choice from Following ....
1 for Rock
2 for Paper
3 for Scissor

Player chooses: 1 (Rock)
```
- The computer's choice is randomly generated and displayed.
- The game announces the result (Win, Lose, or Draw).

## Project Structure

```
RockPaperScissor/
├── README.md
└── rock_paper_scissor.py
```

## Example Output

```text
You chose Rock
Computer chose Paper
Paper beats Rock
You Lose!
```

## Contributing

Contributions are welcome! If you have any ideas for improving the game or adding new features, feel free to fork the repository and submit a pull request.

## Author

- [Aditya Kumar](https://github.com/aditya-kr86)

## License

This project is open-source and available under the MIT License.

## Feedback

If you have any feedback, please reach out via [email](mailto:adityakumargupta082003@gmail.com).
