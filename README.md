# mention-all-bot
mention-all-bot adalah bot telegram yang membantu menyebutkan semua pengguna dalam grup.

Perintah :

```
/start - Tampilkan teks bantuan
/in - Ikut serta untuk menerima sebutan
/out - Menyisih dari menerima sebutan
/all - Sebutkan semua pengguna yang ikut serta
/stats - Tampilkan statistik bot
```
## Deploy Bot Mention

<b>
<a href="https://heroku.com/deploy?template=https://github.com/apisuserbot/Project-Mention"><img src="https://img.shields.io/badge/Deploy Project-Mention-blue?style=badge&logo=heroku"width="310" height="50"/></a>
</b>

## Memasang via termux

```bash
# clone the repo
git clone https://github.com/apisuserbot/Project-Mention.git
cd Project-Mention

# atur token bot dan paswword db Anda
echo "TGBOT_TOKEN=????????" > .env
echo "DB_PWD=????????" >> .env

# menjalankan app
docker-compose up -d
```

## License
GNU GPLv3
