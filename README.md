# cs2-cache-retakes

### Setup
Clone and set up the repo
```bash
git clone https://github.com/Bims-sh/cs2-cache-retakes && \
cd cs2-cache-retakes && \
mkdir -p cs2 && \
chown 1000:1000 cs2
```

### Setup .env
Copy the env example and edit the variables
```
cp .env.example .env
```

### Start
Start the container with docker compose
```bash
docker compose up -d
```
