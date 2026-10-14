# Students — PYMATGEN

**Project:** PYMATGEN  
**Category:** CHEMICAL_MANUFACTURING  
**Upstream:** see BENCH.json  
**Pinned commit:** `e84356b9cd4a2411097d10dc64bf5f331a35109c`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `f75effaea3bc7d239e1b717b7e1f3e0b65d3a141665c7a7fef76149338ff59d7`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `e84356b9cd4a2411097d10dc64bf5f331a35109c`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `f75effaea3bc7d239e1b717b7e1f3e0b65d3a141665c7a7fef76149338ff59d7`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
