# Phase 1: The Server (Docker)

The server handles your DigitalOcean storage links, user accounts, and version tracking. Using Docker is the only recommended way to install it.

1. **Clone the deployment repo:**
   Open your terminal and run:

```bash
git clone https://github.com/ynput/ayon-docker.git
cd ayon-docker

```

2. **Launch the stack:**

```bash
docker compose up -d

```

_This will download and start the AYON backend, frontend, PostgreSQL database, and Redis._ 3. **Initial Web Login:**

- Open your browser and go to `http://localhost:5000` (or your server's IP).
- Create your **Admin account**.
- **Bootstrap:** AYON will ask to "Bootstrap." This automatically downloads the latest core addons (Blender, Maya, etc.) so you don't have to install them manually.
