# IoT → TTN → Oracle → IOTA analysis (Python)

This package produces KPI tables + paper-ready plots from your CSV logs.

## Run
```bash
python analysis_iot_dlt.py --notarize ./logs/notarize_metrics.csv --oracle ./logs/oracle_metrics.csv --out ./analysis_out
```

- `--oracle` is optional (use it if you want RSSI/SNR + uplink-rate + end-to-end join attempt).
- Figures are saved under `analysis_out/figures/`.
- Summary tables are saved as CSV under `analysis_out/`.
