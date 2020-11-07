# discord-prombot

Discord bot meant to watch a server and expose data via a Prometheus exporter

## Initial thoughts

- Use Python3.
- The bot should be read-only. No changes should ever be made to the Discord server.
- This project should lead with a Docker-first mentality. I'm tired of dependency hell.
- It should be possible to load custom modules without major code changes. This will help allow other servers add functionality to the bot that might not make sense globally.
