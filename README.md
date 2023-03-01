# blockchain-in-compose
Local blockchain using Genache CLI + Blockscout Explorer in single docker-compose command.

### Prepare ENV file
Create `.env` file to store the configuration:
```
BLOCKSCOUT_SECRET_KEY_BASE=<secret-key-base>
GANACHE_SEED_PHRASE=<random-seed-phrase-here>
```

### Run Docker Compose

```
docker compose up -d
```

### Access the blockchain

- The blockchain RPC (Genache) will be accessible via port `8545`, configure your wallet to connect to this endpoint.
- Block explorer web UI (Blockscout) is accessible via port `4000`.