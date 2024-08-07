# ffxiv-world-status

This project has been separated into multiple repositories.

| Repository | Description |
|---|---|
| [ffxiv-world-status-api](https://github.com/c032/ffxiv-world-status-api) | Nest.js HTTP API that exposes recent-ish status of FFXIV worlds. |
| [ffxiv-world-status-discord](https://github.com/c032/ffxiv-world-status-discord) | Discord bot that uses `ffxiv-world-status-api`. |
| [ffxiv-world-status-fetch](https://github.com/c032/ffxiv-world-status-fetch) | Go program that runs periodically to update the database that is used by `ffxiv-world-status-api`. |

## How is this deployed?

For now I'm using Docker Swarm on Hetzner.
