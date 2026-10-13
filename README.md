# Self-Healing Server Cluster Student Results Portal

This project is a React + Vite dashboard that combines:

- a student results portal,
- a self-healing cluster control panel,
- live failover and recovery simulation,
- Redis session persistence demo behavior.

## Run locally

```bash
npm install
npm run dev -- --host 0.0.0.0
```

Open the local Vite URL shown in the terminal, usually:

```text
http://localhost:5173/
```

## Build

```bash
npm run build
```

## Features

- Search student records by registration number
- Visualize academic mark sheets and skill radar chart
- Simulate overload, crash, failover, and recovery events
- Watch load-balancing traffic shares and live cluster topology
- Monitor Redis session persistence and event logs
