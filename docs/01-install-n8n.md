# Step 1: Install & Self-Host n8n

We recommend using Docker for fast setup:

```bash
docker run -it --rm \
  -p 5678:5678 \
  -v ~/.n8n:/home/node/.n8n \
  -e N8N_BASIC_AUTH_USER=admin \
  -e N8N_BASIC_AUTH_PASSWORD=securepassword \
  n8nio/n8n
```

Access n8n at: [http://localhost:5678](http://localhost:5678)

Alternative: [n8n Docs → Self-Hosting](https://docs.n8n.io/hosting/)
