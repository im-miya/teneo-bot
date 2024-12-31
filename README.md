# Teneo Auto Ping Bot

An automated bot for managing Teneo connections with proxy support and point tracking.

## Features

- Multi-account support
- Proxy management
- Auto reconnection
- Point tracking
- Token management
- Colorful terminal interface
- Proxy rotation
- Connection status monitoring

## Requirements

- Python 3.10+
- pip
- aiohttp
- colorama
- fake-useragent
- pytz
- aiohttp_socks

## How to use

1. Clone the repository

```bash
git clone https://github.com/im-miya/teneo-bot.git
```

2. Install the requirements

```bash
pip install -r requirements.txt
```

3. Place your accounts in `accounts.json`

```json
[
  {
    "Email": "user@mail.com",
    "Password": "password"
  }
]
```

4. place your proxies in `proxies.txt`

```text
# place your proxies here
# format:
# http://user:password@ip:port
# socks5://user:password@ip:port

# example:
# http://user:password@127.0.0.1:1080
# socks5://user:password@127.0.0.1:1080
```

5. Run the bot

```bash
python bot.py
```

6. Enjoy!
