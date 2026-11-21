# FinOps Low-Code Automation Lab

Lightweight containerized automation engine running **n8n** under strict memory boundaries (`250MB` RAM limit + V8 heap cap) on WSL2 / Ubuntu.

## Resource Constraints
- **Container Memory Limit:** `250MB`
- **V8 Heap Cap:** `192MB` (`--max-old-space-size=192`)
- **CPU Quota:** `0.5` cores
