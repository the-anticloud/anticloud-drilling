# Students — DRILLING

**Project:** DRILLING  
**Category:** OIL_GAS  
**Upstream:** https://github.com/APMonitor/drilling  
**Pinned commit:** `c9de0bba1c55225bbdbb2a0eca75f63cc3b9279b`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `3a2a57f0a9d88c7912a70d9e436a3636e8f3c494cb6ef84ac5a7d384ba328c6a`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `c9de0bba1c55225bbdbb2a0eca75f63cc3b9279b`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `3a2a57f0a9d88c7912a70d9e436a3636e8f3c494cb6ef84ac5a7d384ba328c6a`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
