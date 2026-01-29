# 🧽 Kitchen Cleaning Robot AI

An end-to-end Vision–Language–Action robotic system
for autonomous kitchen cleanup.

## Capabilities
- Object detection & segmentation (YOLO / SAM)
- World modeling
- LLM-based task planning
- Reinforcement learning control
- Sim-to-real transfer

## Quick Start
```bash
docker build -t kitchen-ai .
docker run --gpus all kitchen-ai
