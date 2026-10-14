# Students — KODI

**Project:** KODI  
**Category:** MOVIES_MEDIA  
**Upstream:** https://github.com/xbmc/xbmc  
**Pinned commit:** `60c2c516981b531e44d99c6009867d3458faf22d`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `76486714dd0713445f10b6732cf3db501a033ed33109992b953ef5fe4c00521c`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `60c2c516981b531e44d99c6009867d3458faf22d`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `76486714dd0713445f10b6732cf3db501a033ed33109992b953ef5fe4c00521c`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
