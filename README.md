 █████╗ ██╗  ██╗    ██████╗ ███████╗██╗   ██╗
██╔══██╗██║ ██╔╝    ██╔══██╗██╔════╝██║   ██║
███████║█████╔╝     ██║  ██║█████╗  ██║   ██║
██╔══██║██╔═██╗     ██║  ██║██╔══╝  ╚██╗ ██╔╝
██║  ██║██║  ██╗    ██████╔╝███████╗ ╚████╔╝ 
╚═╝  ╚═╝╚═╝  ╚═╝    ╚═════╝ ╚══════╝  ╚═══╝  
                                             



# Discord AI Bot

This is a Discord bot powered by AK DEV. It responds to questions you send in Discord.

## Setup

1. Clone the repository:
```bash
git clone https://github.com/YOUR_USERNAME/discord-ai-bot.git
cd discord-ai-bot
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Create a `.env` file with your tokens:
```
DISCORD_TOKEN=your_discord_bot_token
OPENAI_API_KEY=your_openai_api_key
```

4. Run the bot:
```bash
python bot.py
```

## Usage
In Discord, type:
```
!ask Your question here
```
The bot will reply using GPT.

## Notes
- Keep your `.env` file private.
- You can change the command prefix in `bot.py`.
