# Educators — EVERSHOP_PRIOR_DOCS

**Project:** EVERSHOP_PRIOR_DOCS  
**Category:** ONLINE_RETAIL  
**Upstream:** https://github.com/evershopcommerce/evershop  
**Pinned commit:** `af0a4e1b1747e627e54053654699548c93dc05d0`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `85fb6d17157242f4d115df927f6471866e83394e5dcec9fe2a71f35ab1deb30e`  
**Date:** October 2026

## Teaching with EVERSHOP_PRIOR_DOCS

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `85fb6d17157242f4d115df927f6471866e83394e5dcec9fe2a71f35ab1deb30e` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
