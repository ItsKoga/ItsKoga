# Hi, I'm Louis 👋

> *Curious enough to ask why, stubborn enough to figure it out.*

I'm an IT specialist apprentice (system integration) from Germany who likes turning ideas into things people actually use: Discord bots for a community of thousands, a photo portfolio with its own image recognition, and small tools that save me time every day. I've been writing Python since 2022 and lately spend a lot of time with Docker, self-hosting and Django.

- 🛠️ Apprenticeship as an IT specialist for system integration (since 2026)
- 🎓 Vocational high school for technology (2023 – 2025)
- 🚒 Volunteer firefighter · 🔭 astronomy nerd · 🎮 gamer

---

## 🔧 What I'm building

### 🐉 Bots for the [Drachen Kult](https://drachenkult.com) community

| Project | What it does | Stack |
|---|---|---|
| **[DKMinigames-bot](https://github.com/ItsKoga/DKMinigames-bot)** | Plugin-based minigame bot with its own web dashboard and Discord login. Plugins for emoji quiz, anagrams, counting, one-word stories and automatic channel rotation. Ships as a multi-arch Docker image (amd64 + arm64) with an Unraid template. | Python · py-cord · FastAPI · SQLite · Docker · GitHub Actions |
| **[DKOster-bot](https://github.com/ItsKoga/DKOster-bot)** | The yearly Easter event: collect chocolate, raw and cooked eggs, bake cakes, throw eggs at friends and fight for the leaderboard. Improved every year since 2024. | Python · py-cord · MySQL |
| **[DKEmoji-bot](https://github.com/ItsKoga/DKEmoji-bot)** | The original emoji guessing game: the bot posts emojis, the community guesses the word. Includes stats, idea submissions and emoji/role search. | Python · py-cord · MySQL |

### 📸 [Fotoportfolio](https://github.com/ItsKoga/Fotoportfolio)

A Django portfolio for motorcycle photography. The interesting part: untagged photos get **rider and bike suggestions** from two small vision models running locally (YOLOS-tiny finds the bike, DINOv2 embeds it), combined with burst detection from EXIF timestamps and a classifier trained on already tagged photos. Deployed as a Gunicorn + Nginx stack, built and published to GHCR by GitHub Actions.

`Django` · `Docker Compose` · `Nginx` · `Portainer`

### 🧪 Smaller things

- **Personal Website**: my portfolio page in plain HTML, CSS and JavaScript.
- **PersonalAgent**: a local Django dashboard that runs tasks through the Claude CLI, tracks token usage and listens for voice commands on macOS.
- **UntisToICAS**: exports my school timetable from WebUntis to an `.ics` calendar.

---

## 🧰 Tech stack

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**Frameworks & libraries**
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![py-cord](https://img.shields.io/badge/py--cord-5865F2?style=flat-square&logo=discord&logoColor=white)
**Infrastructure & tools**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Unraid](https://img.shields.io/badge/Unraid-F15A2C?style=flat-square&logo=unraid&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## 📊 Stats

<p>
  <img src="https://raw.githubusercontent.com/ItsKoga/github-stats/master/generated/overview.svg#gh-dark-mode-only" alt="GitHub stats" />
  <img src="https://raw.githubusercontent.com/ItsKoga/github-stats/master/generated/languages.svg#gh-dark-mode-only" alt="Top languages" />
</p>

---

<sub>Got an idea for a bot or want to collaborate? Open an issue on one of my repos. 🙂</sub>
