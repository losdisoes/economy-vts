# Economy VTS: Advanced Discord Bot for Economy Management 🌟

![Economy VTS](https://img.shields.io/badge/Discord%20Bot%20in%20TypeScript-advanced%20economy%20system-blue)

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Commands](#commands)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)
- [Links](#links)

## Overview

Economy VTS is a powerful Discord bot built with TypeScript. It offers both advanced and standard economy systems, making it perfect for any server looking to add a fun and engaging economic layer to their community. With a new feature added every three days, this bot stays fresh and relevant, ensuring users always have something new to explore.

## Features

- **Advanced Economy System**: Users can earn, spend, and trade virtual currency.
- **Standard Economy Features**: Basic functionalities for those who prefer simplicity.
- **Regular Updates**: New features added every three days.
- **Custom Commands**: Easily customizable commands to suit your server's needs.
- **Slash Commands**: Enhanced user experience with modern command styles.
- **Prefix Support**: Use custom prefixes for commands.
- **JSON Data Storage**: Efficient and reliable data management.

## Installation

To get started with Economy VTS, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/losdisoes/economy-vts.git
   ```

2. Navigate to the project directory:

   ```bash
   cd economy-vts
   ```

3. Install the required packages:

   ```bash
   npm install
   ```

4. Configure your bot token and settings in the `config.json` file.

5. Run the bot:

   ```bash
   npm start
   ```

For the latest releases, visit [Releases](https://github.com/losdisoes/economy-vts/releases). Download the necessary files and execute them as per the instructions.

## Usage

Once the bot is running, it will automatically join your server. Users can interact with the bot using the commands listed below. Ensure that the bot has the necessary permissions to function correctly.

## Commands

### Economy Commands

- **!balance**: Check your current balance.
- **!work**: Earn some currency by completing a task.
- **!daily**: Claim your daily reward.
- **!transfer @user amount**: Transfer currency to another user.
- **!shop**: View items available for purchase.

### Administration Commands

- **!setprefix newPrefix**: Change the command prefix.
- **!reset economy**: Reset the economy data (use with caution).
- **!stats**: View bot statistics.

### Slash Commands

Utilize slash commands for a more streamlined experience. Simply type `/` and the command name to see available options.

## Configuration

The bot uses a `config.json` file for configuration. Key settings include:

- **Token**: Your Discord bot token.
- **Prefix**: The command prefix for the bot.
- **Currency Name**: Customize the name of your virtual currency.

Example `config.json`:

```json
{
  "token": "YOUR_BOT_TOKEN",
  "prefix": "!",
  "currency": "Coins"
}
```

## Contributing

Contributions are welcome! If you have ideas for new features or improvements, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add new feature'`).
5. Push to the branch (`git push origin feature/YourFeature`).
6. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Links

For the latest updates and releases, visit [Releases](https://github.com/losdisoes/economy-vts/releases). You can download the necessary files and execute them as per the instructions provided.

![Join Us on Discord](https://img.shields.io/badge/Join%20Us%20on%20Discord-Chat%20with%20Us-brightgreen)

Explore the repository, contribute, and enjoy the features of Economy VTS!