# file-purge

A lightweight, Dockerized Python utility that automatically deletes files older than **48 hours** from any mapped directory.  
Perfect for cleaning up temporary downloads, logs, caches, or any folder that shouldn’t keep stale files.

---

## 🚀 Features

- **Time-based cleanup** — Deletes files older than 48 hours.
- **Docker-ready** — Runs in an isolated container with minimal dependencies.
- **Configurable target directories** via Docker volume mapping.
- **Safe by default** — Only touches mapped folders.
- **Lightweight footprint** — Runs periodically without heavy resource use.

---

## 📦 Usage

### 1️⃣ Pull the image

```bash
docker pull ghcr.io/dhaevyd/file-purge:latest

