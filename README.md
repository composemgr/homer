# Homer

A self-hosted application for managing homer.

## Installation

### Option 1: Quick Install
```bash
curl -q -LSsf "https://raw.githubusercontent.com/composemgr/homer/main/docker-compose.yaml" | docker compose -f - up -d
```

### Option 2: Git Clone
```bash
git clone "https://github.com/composemgr/homer" ~/.local/srv/docker/homer
cd ~/.local/srv/docker/homer
docker compose up -d
```

### Option 3: Using composemgr
```bash
composemgr install homer
```

## Configuration

See docker-compose.yaml for environment variables and configuration options.

## Documentation

Check the official project documentation for detailed setup and usage information.
