# On-Chain Randomness Lottery Game with Chainlink VRFs

## Overview

Welcome to our Lottery Game project, where we leverage on-chain randomness through Chainlink VRFs (Verifiable Random Functions) to create a fair and transparent lottery experience. In this game, players have the opportunity to participate by adhering to specific rules and conditions, and the winner is selected at random once the maximum number of players has been reached.

## Project Features

- **Lottery Structure:** Each game is designed with a predefined maximum number of players and an entry fee.
- **Player Participation:** Individuals can join the game by meeting the entry requirements.
- **Random Winner Selection:** After reaching the maximum number of players, the system utilizes Chainlink VRFs to randomly select one winner.
- **Prize Distribution:** The chosen winner is awarded an amount equivalent to `maxplayers * entryfee` in ether.

## Getting Started

To explore and contribute to this project, follow these steps:

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/dappCoderr/lottery-game.git
   cd lottery-game
   ```

2. **Install Dependencies:**

   ```bash
   npm install
   ```

3. **Configuration:**
   Adjust configuration files as needed, including maximum players, entry fees, and any other relevant parameters.

4. **Run the Application:**

   ```bash
   npm start
   ```

5. **Contribute:**
   Feel free to contribute by submitting bug reports, feature requests, or even pull requests. Your input is valuable!

## Dependencies

This project relies on the following key dependencies:

- [Chainlink VRF](https://docs.chain.link/docs/verifiable_random_function)
- [Hardhat](https://hardhat.org/hardhat-runner/docs/getting-started)
- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)

Make sure to review the documentation of these dependencies for detailed information.

## Acknowledgments

We would like to express our gratitude to the Chainlink VRF community for providing the tools and resources that make this project possible.

Feel free to reach out if you have any questions or suggestions!

Happy gaming!
