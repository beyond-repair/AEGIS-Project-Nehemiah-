<div align="center">

# Project Nehemiah · AEGIS

### Live **host integrity** — measure change, prove it, decide against a baseline

[![SECURITY](https://img.shields.io/badge/line-SECURITY-0ea5e9?style=for-the-badge)](https://github.com/beyond-repair/ADL-Governance)
[![Contract](https://img.shields.io/badge/validator-forge--aegis-22c55e?style=for-the-badge)](https://github.com/beyond-repair/forge-aegis)

</div>

---

## Why this exists

Antivirus asks “is this malware?”  
Nehemiah asks **what changed**, **can I prove it**, **is it authorized**, and **does the baseline still hold?**

## Why you need it

| You need… | Nehemiah’s job |
|-----------|----------------|
| Continuous host collection | Truth / Graph / Watchman path |
| Policy + deterministic verdict | **Consumes** [forge-aegis](https://github.com/beyond-repair/forge-aegis) — does not reinvent validation math |
| Audit + optional restore | Memory / Restoration pillars (authorized only) |

**You need forge-aegis first** for the offline evidence → policy → PASS/FAIL/INCONCLUSIVE contract.  
Nehemiah is the **live collection and stewardship** layer on top.

## How it works

```text
Host reality
    → Truth (measure)
    → Graph (canonical state)
    → Watchman / Wisdom / Discernment
    → forge-aegis-style validation contract
    → Memory (audit)
    → Restoration only when explicitly authorized
```

**Forge** = meta engineering (schemas, verification, generation).  
**AEGIS** = domain package (firmware, drivers, registry, services, process artifacts, …).

## Architecture pillars

Truth · Graph · Watchman · Wisdom · Discernment · Memory · Restoration · Stewardship

## Status

Ontology and architecture-facing. Align subsystems to the Graph model; **do not** fork independent validation semantics away from forge-aegis v0.1+.

---

**Atomic Dream Labs** · Validator contract: [forge-aegis](https://github.com/beyond-repair/forge-aegis) · [ADL-Governance](https://github.com/beyond-repair/ADL-Governance)
