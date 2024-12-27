# Rock, Scissors, Paper

A simple Python implementation of the classic game "Rock, Scissors, Paper" for the terminal.

## Features

- Play against the computer, which randomly chooses between rock,
scissors, or paper.
- A minimalistic design following the YAGNI (You Aren't Gonna Need It)
principle.
- Object-oriented design.
- Simple terminal-based UI (no graphics—just text!).

## Requirements

Python 3.12

## Installation

1. Clone the repository:

```bash
git clone git@github.com:JamzTyson/RSP_YAGNI.git
```

2. Navigate to the project directory:

```bash
cd rock_scissors_paper
```

## Usage

Run the game with the following command:

```bash
python3 play.py
```

The game will prompt you to enter your choice (rock, paper, or scissors),
and the computer will randomly choose its move. After each round, the result
will be displayed, and the game will ask if you'd like to play again.

**Example**

```bash
Welcome to Rock, Scissors, Paper!
Choose your move:
1. Rock
2. Scissors
3. Paper
Enter your choice (1, 2, or 3): 1
You chose: Rock
Computer chose: Scissors
You win!

Would you like to play again? (y/n): y
```

## How It Works

The game randomly generates the computer's choice from the options
"rock", "scissors", or "paper".

It then compares the player’s choice to the computer’s:

- Rock beats Scissors.
- Scissors beats Paper.
- Paper beats Rock.

The winner is displayed, and the game continues until the player quits.

## License

This project is licensed under the MIT License.
See the [LICENSE](LICENSE) file for details.
