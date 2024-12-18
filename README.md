# Supabase Docker

This is a minimal Docker Compose setup for self-hosting Supabase. Follow the steps [here](https://supabase.com/docs/guides/hosting/docker) to get started.


# Docker compose

Copy the fake env vars

```bash
cp .env.example .env
```

Pull the latest images

```bash
docker compose pull
```

Start the services (in detached mode)

```bash
docker compose up -d

```