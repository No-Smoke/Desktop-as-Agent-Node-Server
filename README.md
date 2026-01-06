# Desktop-as-Agent-Node Server

Intel NUC9 dual-role workstation + services node: GPU-backed LLMs (Ollama), SmythOS orchestration, Caddy reverse proxy, Tailscale VPN.

## Tech Stack

- Ubuntu Budgie 25.04 (X11)
- NVIDIA RTX 3060 12GB + CUDA
- Docker + Docker Compose
- SmythOS Runtime + Studio
- Ollama (GPU-accelerated)
- Caddy (auto TLS)
- Tailscale VPN
- Qdrant + Neo4j on VPS

## Services

| Service | Port |
|---------|------|
| SmythOS Runtime | 7000 |
| SmythOS Studio | 8080 |
| Ollama | 11434 |
| Caddy | 80/443 |

Managed by Task Master AI.
