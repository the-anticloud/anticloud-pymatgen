# Educators — PYMATGEN

**Project:** PYMATGEN  
**Category:** CHEMICAL_MANUFACTURING  
**Upstream:** see BENCH.json  
**Pinned commit:** `e84356b9cd4a2411097d10dc64bf5f331a35109c`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `f75effaea3bc7d239e1b717b7e1f3e0b65d3a141665c7a7fef76149338ff59d7`  
**Date:** October 2026

## Teaching with PYMATGEN

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `f75effaea3bc7d239e1b717b7e1f3e0b65d3a141665c7a7fef76149338ff59d7` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
