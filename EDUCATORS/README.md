# Educators — DRILLING

**Project:** DRILLING  
**Category:** OIL_GAS  
**Upstream:** https://github.com/APMonitor/drilling  
**Pinned commit:** `c9de0bba1c55225bbdbb2a0eca75f63cc3b9279b`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `3a2a57f0a9d88c7912a70d9e436a3636e8f3c494cb6ef84ac5a7d384ba328c6a`  
**Date:** October 2026

## Teaching with DRILLING

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `3a2a57f0a9d88c7912a70d9e436a3636e8f3c494cb6ef84ac5a7d384ba328c6a` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
