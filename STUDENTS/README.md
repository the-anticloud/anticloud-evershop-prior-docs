# Students — EVERSHOP_PRIOR_DOCS

**Project:** EVERSHOP_PRIOR_DOCS  
**Category:** ONLINE_RETAIL  
**Upstream:** https://github.com/evershopcommerce/evershop  
**Pinned commit:** `af0a4e1b1747e627e54053654699548c93dc05d0`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `85fb6d17157242f4d115df927f6471866e83394e5dcec9fe2a71f35ab1deb30e`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `af0a4e1b1747e627e54053654699548c93dc05d0`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `85fb6d17157242f4d115df927f6471866e83394e5dcec9fe2a71f35ab1deb30e`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
