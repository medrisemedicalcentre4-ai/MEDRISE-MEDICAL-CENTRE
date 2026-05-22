# Deployment Guide

## Recommended Platforms
- Vercel
- Render
- Railway
- Docker VPS

## Railway
1. Create Railway project
2. Connect GitHub repository
3. Railway auto-detects Node.js

## Render
1. Create Web Service
2. Connect GitHub repository
3. Build Command:
   pnpm install && pnpm run build

## Docker
```bash
docker-compose up --build
```
