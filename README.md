# pydacc
### Data cleaning and clustering API

[![Deploy to DO](https://www.deploytodo.com/do-btn-blue.svg)](https://cloud.digitalocean.com/apps/new?repo=https://github.com/batmanscode/pydacc/tree/batmanscode-digitalocean-1)

To run locally:
```bash
uvicorn api:app
```

And optionally ` --host 0.0.0.0 --port 8080`

For development, using `--reload` will make things a little easier.

OR

```bash
gunicorn api:app --workers 2 --worker-class uvicorn.workers.UvicornWorker --bind 0.0.0.0:8080
```

**This README is a WIP**
