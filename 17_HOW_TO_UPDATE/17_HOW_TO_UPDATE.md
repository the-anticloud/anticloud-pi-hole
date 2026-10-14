# How to Update — PI_HOLE

**Project:** `PI_HOLE`
**Category:** CONSUMER_ELECTRONICS
**Domain:** consumer electronics
**Date:** 2026-10-07

---

## Update Procedure

### Checking for Updates
```bash
PI_HOLE --version
PI_HOLE check-update
```

### Applying Updates
```bash
pip install --upgrade PI_HOLE
```

### Rolling Back
```bash
pip install PI_HOLE==<previous-version>
```

### Update Policy
- **Security updates:** Applied immediately
- **Feature updates:** Monthly release cycle
- **Breaking changes:** 6-month deprecation notice

## Verification

All 16 checks PASS. Evidence: `ISOLATED_LAB_RESULTS/03_Result_Register.md`.
