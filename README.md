# Open LEN (In Development)

![full_logo_open_len](https://github.com/user-attachments/assets/6f1274e1-9f8d-484c-acbf-379dd97be285)

**Open LEN** is a modular Discord bot featuring built-in artificial intelligence, moderation tools, and interactive features. Designed to enhance community interaction and automate administrative tasks.

## Key Features
- 🔹 **Artificial Intelligence** – Responds to messages, analyzes context, and personalizes interactions.
- 🔹 **Moderation** – Automatic spam restrictions, profanity filtering, and mention control.
- 🔹 **Games & Interactive Features** – Quizzes, quests, and personalized recommendations.

## Installation
### Prerequisites
- Python 3.10+
- Discord bot token

### Launch
```bash
pip install -r requirements.txt --upgrade
python main.py --prod
```

## Configuration
Before running, edit the `.env` file:
```ini
DEBUG_MODE=false

# Discord Bot Token
DISCORD_TOKEN=TOKEN

# API Keys
MISTRAL_API_KEY=TOKEN
```

## Usage
Example commands:
```bash
!"Hi, LEN"
!violation @User "Spam"
!settings
```

## License
This project is distributed under the MIT license.

---

> ⚡ Open LEN is evolving! We welcome your ideas and contributions!  
> The bot's open-source release is coming soon.
