# JavaScript Slot Machine Game



This JavaScript program is a version of the classic slot machine game. It allows players to deposit money, choose the number of lines to bet on, and place bets on each line. The game then randomly generates slot machine spins and calculates the player's winnings based on the symbols that align on the selected lines.

**Note:** This is the JavaScript version of the [Python](https://github.com/StephSteel/pySlotMachine) slot machine project.

## Features

- **Deposit**: Players can deposit an initial amount of money to start playing.
- **Number of Lines**: Players can choose the number of lines they want to bet on, between 1 and 3.
- **Bet Amount**: Players can set their bet amount per line, with a minimum of $1 and a maximum of the balance divided by the number of lines.
- **Spin**: The game generates random slot machine spins with 3 rows and 3 columns filled with symbols.
- **Winnings**: Winnings are calculated based on the symbols that align on the selected lines, with different symbols having different values.
- **Balance**: The player's balance is updated after each spin, and they can choose to continue playing or quit.

## Symbols and Values

The game includes four symbols with corresponding symbol counts and values:

- Symbol "A" has a count of 2 and a value of 5.
- Symbol "B" has a count of 4 and a value of 4.
- Symbol "C" has a count of 6 and a value of 3.
- Symbol "D" has a count of 8 and a value of 2.

## How to Play

1. **Deposit**: Enter the initial amount of money you want to deposit (must be greater than $0).

2. **Number of Lines**: Choose the number of lines you want to bet on (1 to 3).

3. **Bet Amount**: Set your bet amount per line (between $1 and the maximum available based on your balance and lines).

4. **Spin**: The game will display the slot machine spins and calculate your winnings.

5. **Winnings**: You will be informed of your winnings, and if you win on any specific lines.

6. **Continue Playing**: Type "y" to continue playing or any other key to quit.

7. **Balance**: Your balance will be updated after each spin, and you can check it at any time.
