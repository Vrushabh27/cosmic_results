# Cosmic — MolmoSpaces benchmark results

Leaderboard result files for **Cosmic** (Geodesic), evaluated on the [MolmoSpaces](https://github.com/allenai/molmospaces) benchmark suite (Franka, joint-position action space), September 2026.
Each `Cosmic_<benchmark>_oracle.csv` is produced by the official `scripts/benchmarks/eval_to_csv.py --success-condition oracle`; `Cosmic_all_csvs.zip` bundles all eleven.

| Benchmark | Episodes | Success rate |
|---|---|---|
| Pick-v1.1 | 1000 | 62.6% |
| Pick-v1.5 | 1000 | 61.1% |
| Pick-v2-classic | 1000 | 51.4% |
| Pick-v2-filament | 1000 | 49.1% |
| Pick-v2-rand-cam | 1000 | 53.0% |
| Pick&Place-v1 | 1000 | 44.7% |
| Pick&Place-v2 | 1000 | 40.7% |
| Pick&Place-color-v2 | 1000 | 41.7% |
| Pick&Place-NextTo-v2 | 1000 | 43.3% |
| Open-v1 | 1000 | 58.5% |
| Close-v1 | 915 | 87.9% |

Per-episode trajectories, scored-episode manifests and logs: https://huggingface.co/datasets/Vrushabh27/cosmic-molmospaces-eval
