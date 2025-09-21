<a href="https://www.codacy.com/gh/Eldacgithah/Laherter/dashboard"><img src="https://app.codacy.com/project/badge/Grade/97e3ea868f9344a5aa6e4d874f83db14"/></a> <a href="#"><img src="https://img.shields.io/github/languages/code-size/Eldacgithah/Laherter"/></a> <a href="#"><img src="https://img.shields.io/github/issues-raw/Eldacgithah/Laherter"/></a> <a href="#"><img src="https://img.shields.io/github/license/Eldacgithah/Laherter"/></a> <a href="#"><img src="https://img.shields.io/github/commit-activity/m/Eldacgithah/Laherter"/></a><br> <a href="#"><img src="https://img.shields.io/github/forks/Eldacgithah/Laherter?style=flat-square"/></a> <a href="#"><img src="https://img.shields.io/github/stars/Eldacgithah/Laherter"/></a> <a href="https://github.com/psf/black"><img src="https://img.shields.io/badge/code%20style-black-000000.svg" alt="Code style: black"></a><br>

---

**⚠️ Disclaimer / Дисклеймер**

EN: This project is a fork of [Legacy](https://github.com/Crayz310/Legacy).
The fork author takes **no responsibility** for any consequences: account bans, deleted messages, malicious modules or leaked sessions.
By using Laherter, you do so entirely **at your own risk**.

RU: Этот проект — форк [Legacy](https://github.com/Crayz310/Legacy).
Автор форка **не несёт ответственности** за последствия: блокировки аккаунтов, удалённые сообщения, вредоносные модули или утечки сессий.
Используя Laherter, вы делаете это **на свой страх и риск**.

---

**🚀 Installation / Установка**

EN (Manual installation):

```bash
apt update && apt install git python3 -y && git clone https://github.com/Eldacgithah/Laherter && cd Laherter && pip install -r requirements.txt && python3 -m legacy
```

RU (Ручная установка):

```bash
apt update && apt install git python3 -y && git clone https://github.com/Eldacgithah/Laherter && cd Laherter && pip install -r requirements.txt && python3 -m legacy
```

> EN: Even though the folder is named `Laherter`, the run command remains `python3 -m legacy`.
> RU: Несмотря на то, что папка называется `Laherter`, запуск всегда через `python3 -m legacy`.

EN (Docker):

```bash
git clone https://github.com/Eldacgithah/Laherter && cd Laherter && sudo docker build . -t Eldacgithah/laherter:latest
```

RU (Docker):

```bash
git clone https://github.com/Eldacgithah/Laherter && cd Laherter && sudo docker build . -t Eldacgithah/laherter:latest
```

```bash
sudo docker run --restart=unless-stopped --name <container name> -p <port>:8080 --detach -it Eldacgithah/laherter:latest
```

---

**✨ Changes / Изменения**

EN: Nothing has been added yet. The project is still in development.

RU: Ничего пока не внесено. Проект находится в разработке.

---

**📋 Requirements / Требования**

* Python **3.9–3.12**
* API\_ID and API\_HASH from [my.telegram.org](https://my.telegram.org/apps)

---

**📚 Documentation / Документация**

* [Developer docs (archived)](https://web.archive.org/dev.hikka.pw)
* [User docs (archived)](https://web.archive.org/hikka.pw)

---

**🛡️ Warning / Предупреждение**

EN: This project is provided "as is". It is highly recommended to enable API Flood protection (`.api_fw_protection`) and not install many modules at once. By using Laherter, you automatically agree with all possible risks.

RU: Этот проект предоставляется "как есть". Настоятельно рекомендуется включить защиту от API Flood (`.api_fw_protection`) и не устанавливать много модулей одновременно. Используя Laherter, вы автоматически соглашаетесь со всеми возможными рисками.

---

**💎 Special thanks / Благодарности**

* [Hackintosh5](https://gitlab.com/hackintosh5) — creator of FTG, the base of Hikka / автор FTG, основа Hikka
* [Hikariatama](https://github.com/beveiled) — creator of Hikka, the base of Legacy / автор Hikka, основа Legacy
* [Crayz310](https://github.com/Crayz310) — creator of Legacy, the base of Laherter / автор Legacy, основа Laherter
* [Codrago](https://github.com/coddrago) — patches from Heroku / патчи из Heroku
* [Codwiz](https://t.me/GunyaKshin) — Ukrainian translation / украинский перевод
* [ɴᴇᴛ『s』ᴛᴀʟᴋ『2』『4』](https://t.me/Admt_450) — testing, bug reports, Ukrainian translation / тестирование, баги, перевод
* [Lonami](https://t.me/lonami) — creator of Telethon / автор Telethon

🔄 EN: Laherter itself is also a fork.
🔄 RU: Laherter сам по себе тоже является форком.
