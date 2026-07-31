# Практична робота: Docker та Docker Compose

**Студент:** Лендєл Е.Т.
**Курс:** 3 курс
**Група:** 232.2

---

## Вправа 1 — Docker + Compose

### 1. Версія Docker
Команда: `docker --version`
Вивід:
```text
C:\Windows\System32>docker --version
Docker version 29.3.1, build c2be9cc
2. Версія Docker Compose
Команда: docker compose version
Вивід:C:\Windows\System32>docker compose version
Docker Compose version v5.1.1
Перевірка роботи Docker
Команда: docker run --rm hello-world
Вивід:C:\Windows\System32>docker run --rm hello-world
Unable to find image 'hello-world:latest' locally
latest: Pulling from library/hello-world
4f55086f7dd0: Pull complete
d5e71e642bf5: Download complete
Digest: sha256:c3cbe1cc1aa588a64951ac6286e0df7b27fe2e6324b1001c619bb358770c0178
Status: Downloaded newer image for hello-world:latest

Hello from Docker!
This message shows that your installation appears to be working correctly.
Вправа 3 — docker-compose + latest npm
1. Запуск docker-compose (версія npm)
Команда: docker compose run --rm npm npm -v
Вивід:Image docker-task-npm Built
Container docker-task-npm-run-3b27458ec0b4 Creating
Container docker-task-npm-run-3b27458ec0b4 Created
12.0.2
Запуск docker-compose (версія node)
Команда: docker compose run --rm npm node --version
Вивід:Container docker-task-npm-run-d67612a77af8 Creating
Container docker-task-npm-run-d67612a77af8 Created
v24.18.1
