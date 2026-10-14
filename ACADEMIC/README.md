# Academic Use — SYSBENCH

**Project:** SYSBENCH  
**Category:** LAPTOPS  
**Upstream:** see BENCH.json  
**Pinned commit:** `f110afa8023c7924b1ba00177232a9090624acb5`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `de52e6362a34b084c629f1da9f9beaa33ebe397bfd445e1d83ee7f2e58625b64`  
**Date:** October 2026

## Scope

SYSBENCH is available for academic research under the Apache 2.0 terms of the
Anticommons 0.1.0 dual licence. Citation details are in `23_HOW_TO_CITE`.

## What is available to researchers

- The full upstream source, pinned at `f110afa8023c7924b1ba00177232a9090624acb5`
- The 16-check assurance register with per-check evidence and hashes
- The AIOSS ledger attesting the project artifacts
- Benchmark output in `BENCH.json`

## Reproducing the result

```
python tools/run_bench.py --out BENCH.json
```

Then recompute any row's SHA3-256 from `ISOLATED_LAB_RESULTS/04_Evidence/`.

## Contact

lois@0-1.gg · 0-1.gg
