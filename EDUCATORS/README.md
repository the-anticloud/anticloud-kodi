# Educators — KODI

**Project:** KODI  
**Category:** MOVIES_MEDIA  
**Upstream:** https://github.com/xbmc/xbmc  
**Pinned commit:** `60c2c516981b531e44d99c6009867d3458faf22d`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `76486714dd0713445f10b6732cf3db501a033ed33109992b953ef5fe4c00521c`  
**Date:** October 2026

## Teaching with KODI

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `76486714dd0713445f10b6732cf3db501a033ed33109992b953ef5fe4c00521c` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
