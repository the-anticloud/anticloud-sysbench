# Ethics — SYSBENCH

**Project:** SYSBENCH  
**Category:** LAPTOPS  
**Upstream:** see BENCH.json  
**Pinned commit:** `f110afa8023c7924b1ba00177232a9090624acb5`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `de52e6362a34b084c629f1da9f9beaa33ebe397bfd445e1d83ee7f2e58625b64`  
**Date:** October 2026

## Position

SYSBENCH is packaged for offline deployment with a verifiable audit trail. The
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
