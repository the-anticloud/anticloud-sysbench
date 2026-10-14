# Onboarding — SYSBENCH

**Project:** SYSBENCH  
**Category:** LAPTOPS  
**Upstream:** see BENCH.json  
**Pinned commit:** `f110afa8023c7924b1ba00177232a9090624acb5`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `de52e6362a34b084c629f1da9f9beaa33ebe397bfd445e1d83ee7f2e58625b64`  
**Date:** October 2026

## First hour

1. Read `README.md` — what the project is and what it measures.
2. Read `ISOLATED_LAB_RESULTS/03_Result_Register.md` — the 16 checks and their
   evidence hashes.
3. Run the suite: `python tools/run_bench.py --out BENCH.json`.
4. Verify a hash: recompute SHA3-256 of a file in `04_Evidence/` and compare.

## First day

- `10_TECHNICAL_HANDOFF` — architecture and interfaces
- `11_TUTORIAL_DEVELOPERS` — build and test
- `18_COMMAND_LINE_INTERFACE` — CLI reference
- `27_DEPENDENCIES` — the offline dependency mirror

## Getting help

lois@0-1.gg · 0-1.gg
