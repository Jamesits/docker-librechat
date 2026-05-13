![Works - On My Machine](https://img.shields.io/badge/Works-On_My_Machine-2ea44f)
![Project Status - Feature Complete](https://img.shields.io/badge/Project_Status-Feature_Complete-2ea44f)

[LibreChat](https://www.librechat.ai/) deployment template with:

- Docker Compose config
- PostgreSQL as the only database
- Admin Panel

## Usage

```shell
mkdir -p -- ./deployment/librechat
cp -rv -- ./example/* ./deployment/
sudo chown -R 100999:100999 -- ./deployment/librechat
docker compose up -d
```
