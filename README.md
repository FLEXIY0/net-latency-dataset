# net-latency-dataset

Hourly snapshots of endpoint reachability and latency probes, produced by an automated job.
Each snapshot keeps only endpoints that answered during the latest probe round; the set is
re-validated every 15 minutes.

| File | Contents |
|------|----------|
| `data/probe_set_a.txt` | endpoint set A (encoded) |
| `data/probe_set_b.txt` | endpoint set B (encoded) |
| `data/probe_set_c.txt` | endpoint set C (encoded) |

Last snapshot: 09.10.2026 01:52 (UTC+3)

Data is provided as-is, without any guarantee of availability or accuracy.
Released under CC0 1.0 (see `LICENSE`).
