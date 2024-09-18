# Units Network Airdrop bot
Automate transactions in Units Network Testnet using multiple Private Keys.

## Requirements

- Node.js
- npm (Node Package Manager)

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/frankrichardhall/Units-Network-Airdrop-bot.git
   cd Units-Network-Airdrop-bot
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Prepare private keys:**

   - Create or edit `privateKeys.json` to include your Ethereum private keys as an array of strings. Each private key should be enclosed in double quotes.

   **Example `privateKeys.json` (correct format):**
   ```json
   [
       "private_key_1_here",
       "private_key_2_here"
   ]
   ```

   Ensure each private key string is correctly formatted as shown above.

## Usage

- **Run the application:**

  ```bash
  npm start
  ```

- Follow the prompts to enter the number of transactions to send per private key.