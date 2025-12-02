# FastAPI Docker example

Files created in this folder:

- `app/main.py` - minimal FastAPI app
- `requirements.txt` - Python deps
- `Dockerfile` - build container
- `docker-compose.yml` - compose to run the service

Build and run (Windows `cmd.exe`):

From the repository root (recommended):

```bash
docker compose up --build
```

After the service is up, open http://localhost:8000/ and http://localhost:8000/health
