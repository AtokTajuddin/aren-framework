# Aren Framework

> *A Simple C++ Web Framework, support REST API Development*

## Features (In-Development)

- **Zero Setup**            : Header-only,dependencies auto-download
- **Microservice Ready**    : Sub-routers & health checks
- **Security built-in**     : JWT,CORS,Rate Limiting 

---

## Quick Start (~5 minutes)

```bash
# Install CLI
curl -L https://github.com/yourusername/aren-framework/releases/latest/download/aren -o /usr/local/bin/aren
chmod +x /usr/local/bin/aren

# Create project
aren new my-api
cd my-api

# Run dev server
aren dev