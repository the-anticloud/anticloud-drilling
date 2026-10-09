# Ethics — DRILLING

**Project:** DRILLING  
**Category:** OIL_GAS  
**Upstream:** https://github.com/APMonitor/drilling  
**Pinned commit:** `c9de0bba1c55225bbdbb2a0eca75f63cc3b9279b`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `3a2a57f0a9d88c7912a70d9e436a3636e8f3c494cb6ef84ac5a7d384ba328c6a`  
**Date:** October 2026

## Position

DRILLING is packaged for offline deployment with a verifiable audit trail. The
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
