# Newton-Raphson Power Flow

Educational Python implementation of Newton-Raphson AC power-flow analysis.

## Contents

| File | Purpose |
|---|---|
| `newton_raphson_power_flow.py` | Main Newton-Raphson solver script. |
| `33Bus.txt`, `33Line.txt` | Default 33-bus input data read by the script. |
| `3Bus.txt`, `3Line.txt` | Smaller historical test inputs. |
| `result.csv` | Preserved historical result file. |

The current script reads the 33-bus input files, iterates until the power mismatch is below its configured tolerance, prints the loss and iteration count, and writes `NRPF_result.csv`.

## Requirements

- Python 3.8 or later
- `numpy`, `pandas`, and `matplotlib`

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install -r requirements.txt
python newton_raphson_power_flow.py
```

Run the command from the repository root so the relative input paths resolve correctly.

## Cleanup status

This cleanup branch retains all historical data and normalizes the main source filename to `newton_raphson_power_flow.py`. The script stays at the repository root so its relative data paths continue to work. Output naming will be standardized after a verified run.

## License and citation

A reuse license and citation guidance will be added after the intended reuse terms are chosen.
