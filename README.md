# Newton-Raphson Power Flow

Educational Python implementation of Newton-Raphson AC power-flow analysis.

## Contents

| File | Purpose |
|---|---|
| `Newton-Raphson power flow.py` | Main Newton-Raphson solver script. |
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
python "Newton-Raphson power flow.py"
```

Run the command from the repository root so the relative input paths resolve correctly.

## Cleanup status

This documentation-first branch retains all historical data and source files. The source filename and output naming will be normalized only after a verified run and an old-to-new path record.

## License and citation

A reuse license and citation guidance will be added after the intended reuse terms are chosen.
