# Ethics — EVERSHOP_PRIOR_DOCS

**Project:** EVERSHOP_PRIOR_DOCS  
**Category:** ONLINE_RETAIL  
**Upstream:** https://github.com/evershopcommerce/evershop  
**Pinned commit:** `af0a4e1b1747e627e54053654699548c93dc05d0`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `85fb6d17157242f4d115df927f6471866e83394e5dcec9fe2a71f35ab1deb30e`  
**Date:** October 2026

## Position

EVERSHOP_PRIOR_DOCS is packaged for offline deployment with a verifiable audit trail. The
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
