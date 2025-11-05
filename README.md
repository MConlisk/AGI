# Deterministic Fully-Coupled Engine v1

## Requirements
- Python 3.10+
- pygame (2.6.x recommended)
- numpy

## Run
From the project root (folder containing `experiments/`):
```
python -m experiments.experiment01
```

If you prefer running the file directly:
```
python experiments/experiment01.py
```
(Absolute imports are used, so both should work if you run from the project root.)

## Notes
- Configuration lives in `configuration/` (manifolds, feedback couplings, sensors).
- Portrait dashboard: 3 MRI-style slices (from the first manifold) + 5 EEG traces + HUD.
- No randomness. Stability emerges from budgets, coupling, and delay lines.