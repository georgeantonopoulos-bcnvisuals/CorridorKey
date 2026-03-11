# CorridorKey Installation Findings

## Environment Check
- **OS**: Linux (george.antonopoulos@internal.bcnvisuals.com)
- **uv**: Not found. Needs installation.
- **Checkpoints**:
  - `CorridorKeyModule/checkpoints/`: Empty
  - `gvm_core/weights/`: Empty
  - `VideoMaMaInferenceModule/checkpoints/`: Empty

## Installation Strategy
1. Install `uv` using the official script: `curl -LsSf https://astral.sh/uv/install.sh | sh`.
2. Run `uv sync` to set up the environment.
3. Download models:
   - CorridorKey v1.0 Model (`CorridorKey.pth`) -> `CorridorKeyModule/checkpoints/CorridorKey.pth`
   - GVM Weights (Optional)
   - VideoMaMa Weights (Optional)
