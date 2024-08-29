# Rock Paper Scissors Game - Aptos Project

![Aptos](https://pbs.twimg.com/media/GVU9bWDWQAAqHAs?format=jpg&name=small)

Welcome to the **Rock Paper Scissors** game powered by the Aptos blockchain! This repository contains the smart contract code for an interactive blockchain-based Rock Paper Scissors game. The project is built on the Aptos blockchain, leveraging its capabilities to enable decentralized gameplay with transparent rules and results.

## Features

### **Endless Gameplay**
   - Players can restart a new game after the current game ends, allowing for continuous play without redeploying the contract. This functionality is implemented through the `reset_game` function. Players can enjoy multiple rounds of the game seamlessly.

## How to Play

### Prerequisites
- Install the Aptos CLI.
- Ensure you have an Aptos-compatible wallet (e.g., Petra, Martian) with some APT tokens.

### Smart Contract Deployment
1. Clone the repository:
```bash
   git clone https://github.com/AgosVenezia/Aptos-RockPaperScissors.git
   cd Aptos-RockPaperScissors
```

2. Deploy the smart contract:
```bash
   aptos move publish
```

3. Interact with the contract using your preferred method (e.g., Aptos CLI, block explorer, etc.).

## Smart Contract Functions

### Game Logic

- **start_game:** Initializes a new game and sets up the game state.
- **set_player_move:** Allows the player to set their move (rock, paper, or scissors).
- **randomly_set_computer_move:** Randomly sets the computer's move using the Aptos randomness module.
- **finalize_game_results:** Finalizes the game and determines the winner.
- **reset_game:** Resets the game state for continuous play.

## Video Demo

![Youtube](https://youtu.be/Yvbr5dnPbKk?si=fd71UhfPi0PrCPFt)

## Contribution

Feel free to contribute to this project! If you have ideas for additional features or improvements, open an issue or submit a pull request. I appreciate your feedback and involvement.

#### [A project by Agostina Venezia for StackUp](https://earn.stackup.dev/)