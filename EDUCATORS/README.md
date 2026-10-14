# Educators — SYSBENCH

**Project:** SYSBENCH  
**Category:** LAPTOPS  
**Upstream:** see BENCH.json  
**Pinned commit:** `f110afa8023c7924b1ba00177232a9090624acb5`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `de52e6362a34b084c629f1da9f9beaa33ebe397bfd445e1d83ee7f2e58625b64`  
**Date:** October 2026

## Teaching with SYSBENCH

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `de52e6362a34b084c629f1da9f9beaa33ebe397bfd445e1d83ee7f2e58625b64` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
