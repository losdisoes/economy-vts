# Discord Economy Bot

A Discord bot with economy features, written in TypeScript.

## Features

- **Daily Rewards**: Collect daily coins (890-1070)
- **Balance Check**: View your or others' balance
- **Transfer System**: Give coins to other users
- **Leaderboard**: View the richest users
- **Profile System**: View user profiles with rank information

## Commands

### Slash Commands
- `/daily` - Collect daily reward
- `/balance [user]` - Check balance
- `/give <user> <amount>` - Give coins to user
- `/leaderboard [page]` - View richest users
- `/profile [user]` - View user profile

### Prefix Commands
- `daily` - Collect daily reward
- `balance [@user]` - Check balance
- `give @user <amount>` - Give coins to user
- `leaderboard [page]` - View richest users (`lb` or `top` aliases)
- `profile [@user]` - View user profile (`p` or `prof` aliases)

## Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/economy-bot.git
cd economy-bot
```

2. Install dependencies
```bash
npm install
```

3. Build the project
```bash
npm run build
```

4. Start the bot
```bash
npm start
```

## Configuration

Create a `config.json` file in the root directory:

```json
{
  "token": "YOUR_BOT_TOKEN",
  "prefix": "YOUR_PREFIX"
}
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. 