# Discord-GMGN-Chat-Bot

Discord-GMGN-Chat-Bot is a Node.js bot that uses the `discord-simple-api` package to send "Good Morning" and "Good Night" messages to specified Discord channels at 08:00 UTC and 20:00 UTC respectively.

## Features

- Sends "GM" (Good Morning) at 08:00 UTC to specified channels.
- Sends "GN" (Good Night) at 20:00 UTC to specified channels.
- Reads target channel IDs from a text file.
- Utilizes `.env` for token security.
- Colorful console output for better readability and debugging.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js installed on your system.
- A Discord bot token. [Learn how to create a bot and get a token](https://discord.com/developers/applications).
- The channel IDs where the bot will send messages.

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/dante4rt/Discord-GMGN-Chat-Bot.git
   ```
2. Navigate to the repository directory:
   ```sh
   cd Discord-GMGN-Chat-Bot
   ```
3. Install the necessary packages:
   ```sh
   npm install
   ```
4. Create a `.env` file in the root directory and add your Discord bot token:
   ```
   DISCORD_TOKEN=your-discord-bot-token
   ```
5. Add channel IDs to `channels.txt`, one ID per line.

## Usage

To start the bot, run the following command:

```sh
node index.js
```

The bot will automatically send "GM" and "GN" messages at the specified times.

## Contributing

Contributions to the Discord-GMGN-Chat-Bot are welcome. If you have a suggestion that would improve this, please fork the repository and create a pull request.

## Contact

If you have any questions or want to get in touch, please open an issue on the GitHub repository.

Enjoy your automated Discord greetings!