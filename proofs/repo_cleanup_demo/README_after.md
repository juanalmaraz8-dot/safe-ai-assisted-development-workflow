# Repo Cleanup Demo
## Purpose
This small demo repo shows how a messy project can be cleaned up with a safe AI-assisted workflow.
## Files
- `report.py`: simple Python script that summarizes a list of items.
- `Makefile`: contains the project test command.
- `.gitignore`: prevents Python cache files from entering git.
## Run
```bash
python3 report.py
```
## Test
```bash
make test
```
The test checks that `report.py` compiles successfully.
## Workflow note
This repo is used as a client-style cleanup demo for RealityOS / AI Runner:
plan → sandbox edit → test → diff → approval → source apply → source test → git commit → checkpoint.
