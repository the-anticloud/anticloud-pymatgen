# Ethics — PYMATGEN

**Project:** PYMATGEN  
**Category:** CHEMICAL_MANUFACTURING  
**Upstream:** see BENCH.json  
**Pinned commit:** `e84356b9cd4a2411097d10dc64bf5f331a35109c`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `f75effaea3bc7d239e1b717b7e1f3e0b65d3a141665c7a7fef76149338ff59d7`  
**Date:** October 2026

## Position

PYMATGEN is packaged for offline deployment with a verifiable audit trail. The
ethical questions this raises are answered by making the system's behaviour
checkable rather than by policy statements.

## The four commitments

1. **No hidden egress.** The deployment has no external API dependency; this is
   testable by running it with the network disconnected.
2. **Attributable output.** Every artifact is recorded in a hash chain, so what
   the system produced can be reconstructed.
3. **Operator control.** The institution owns the hardware and the keys.
4. **Refusal to overclaim.** Where a certification is not held, the project says
   so rather than implying it.

## Dual use

This project is packaged for civilian and public-sector deployment. Where an
upstream has dual-use characteristics, the licence gate and the reference-only
marking in `BENCH.json` record that.
