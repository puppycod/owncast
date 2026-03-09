Owncast + Caddy (Docker Setup)

This guide explains how to run Owncast with Caddy using Docker Compose.

📁 1. Create Required Directories

Create two directories where you want to store the application and its data:

mkdir -p /home/user/owncast

mkdir -p /home/user/owncastdata

/home/user/owncast → Application files

/home/user/owncastdata → Persistent data storage

📄 2. Create Configuration Files

Inside the /home/user/owncast directory, create the following files:

docker-compose.yml

Caddyfile

Make sure both files are properly configured before continuing.

▶ 3. Start the Containers

Navigate to the Owncast directory:

cd /home/user/owncast

Start the containers:
docker compose up

Verify that everything starts correctly.

⏹ 4. Run in Detached Mode (Optional)

To stop the containers, press:
Ctrl+C

To run the containers in the background (detached mode), use:
docker compose up -d

The containers will now run in the background.

📄 5. How to use

https://owncast.online/docs/
