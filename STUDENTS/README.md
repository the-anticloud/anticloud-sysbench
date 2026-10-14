# Students — SYSBENCH

**Project:** SYSBENCH  
**Category:** LAPTOPS  
**Upstream:** see BENCH.json  
**Pinned commit:** `f110afa8023c7924b1ba00177232a9090624acb5`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `de52e6362a34b084c629f1da9f9beaa33ebe397bfd445e1d83ee7f2e58625b64`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `f110afa8023c7924b1ba00177232a9090624acb5`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `de52e6362a34b084c629f1da9f9beaa33ebe397bfd445e1d83ee7f2e58625b64`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
