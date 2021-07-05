# mention-all-bot
mention-all-bot adalah bot telegram yang membantu menyebutkan semua pengguna dalam grup.

Perintah :

```
/start - Display help text
/in - Opt-in to receive mentions
/out - Opt-out of receiving mentions
/all - Mention all opted-in users
/stats - Display bot stats
```

## Installation

```bash
# clone the repo
git clone https://github.com/apisuserbot/Project-Mention.git
cd Project-Mention

# set your bot token and db password
echo "TGBOT_TOKEN=????????" > .env
echo "DB_PWD=????????" >> .env

# run the app
docker-compose up -d
```

## License
GNU GPLv3
