# moodle

> Click To Deploy Moodle LXP — SFIA-compatible Learning Experience Platform

[![Sync](https://github.com/opensaasapps/moodle/actions/workflows/sync.yml/badge.svg)](https://github.com/opensaasapps/moodle/actions/workflows/sync.yml) [![Docker](https://github.com/opensaasapps/moodle/actions/workflows/docker.yml/badge.svg)](https://github.com/opensaasapps/moodle/actions/workflows/docker.yml) [![Docker Pulls](https://img.shields.io/docker/pulls/thefractionalpm/moodle)](https://hub.docker.com/r/thefractionalpm/moodle)

Upstream: [moodle/moodle](https://github.com/moodle/moodle) · Auto-synced daily

---

## One-Command Deploy

```bash
cp .env.example .env && nano .env
docker compose up -d
```

## Coolify / Dokploy

1. New service → **Docker Compose**
2. Paste `docker-compose.yml`
3. Set env vars in UI
4. Deploy

## Environment Variables

| Variable | Required | Description |
|---|---|---|
| `MOODLE_DATABASE_HOST` | ⚪ | |
| `MOODLE_DATABASE_NAME` | ⚪ | |
| `MOODLE_DATABASE_USER` | ⚪ | |
| `MOODLE_DATABASE_PASSWORD` | ✅ | |
| `MOODLE_USERNAME` | ⚪ | |
| `MOODLE_PASSWORD` | ✅ | |
| `MOODLE_EMAIL` | ⚪ | |
| `MOODLE_SITE_NAME` | ⚪ | |
| `MOODLE_HOST` | ⚪ | |
| `MOODLE_SMTP_HOST` | ✅ | |
| `MOODLE_SMTP_PORT` | ⚪ | |
| `MOODLE_SMTP_USER` | ✅ | |
| `MOODLE_SMTP_PASSWORD` | ✅ | |
| `MOODLE_SMTP_PROTOCOL` | ⚪ | |

## Image

```
docker pull bitnami/moodle:latest
docker pull thefractionalpm/moodle:latest
```

## Ports

| Port | Service |
|---|---|
| `8080` | Main app |

---

*Part of the [OpenSaaSApps](https://github.com/opensaasapps) Click-To-Deploy collection.*
