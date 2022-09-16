# blockchain-in-compose
Local blockchain using Genache CLI + Blockscout Explorer in single docker-compose command.

[WIP]

- Change the seed data on the Genache command `--seed "your-seed-phrase-here"`
- Set the `SECRET_KEY_BASE` data on blockscout environment variable
- Optionally set the password for postgres database
- Optionally change the port binding, avoid exposing unnecessary connection
- Run the compose: `docker compose up`
