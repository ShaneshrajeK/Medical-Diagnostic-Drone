# Medical Drone

Short description:
A medical delivery / rescue drone project. Contains a script that should be run after spawning ArduCopter in Gazebo and connecting to QGroundControl (QGC), 3D-printed attachment `.stl` files and demonstration media.

## Repo layout
- `run_after_spawn.py` — Python script to run after ArduCopter is spawned and QGC connected.
- `stl/` — 3D-printed attachment files.
- `media/images/` — photos.
- `media/videos/` — demo videos.

## Requirements
Create a virtual environment and install dependencies listed in `requirements.txt`:
```bash
python3 -m venv .venv
source .venv/bin/activate    # Windows: .venv\Scripts\Activate.ps1
pip install -r requirements.txt
