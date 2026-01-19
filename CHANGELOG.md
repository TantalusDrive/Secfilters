# Changelog

This document tracks **meaningful, user-relevant events** in the lifecycle of this repository.

This project follows an **event-based versioning model**: only changes that affect security scope, threat models, or list availability are documented here.  
Minor rule tuning, exception adjustments, or refactors are excluded.

---

## [v1.0.1] - 2026-01-19

### Initial public release

First public release of the **Security Filter Lists** repository.  
Introduced:

- **IDN Homograph & Favicon Security List**  
  - Available in uBlock Origin, AdGuard, Brave Shields, and AdBlock Plus formats.

Defined repository-wide design principles:  
- security-first scope  
- conservative filtering  
- low churn / long-term stability  
- explicit exceptions to minimize false positives and site breakage

Established non-commercial, share-alike licensing model (CC BY-NC-SA 4.0).

---

Future versions will be released **only** when:  
- a new class of security abuse is addressed,  
- the scope or philosophy of an existing list changes,  
- or a new list is added to the repository.
