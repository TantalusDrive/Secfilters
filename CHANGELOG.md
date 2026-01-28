# Changelog

This document tracks meaningful, user-relevant events in the repository lifecycle.<br>
We follow an event-based versioning approach: only changes that affect security scope, threat models, or list availability are recorded. Minor rule tuning, exception adjustments, or formatting refactors are not included.

### Future versions

Updates will only be recorded when:
- A new class of security abuse is addressed.  
- The scope or philosophy of an existing list changes.  
- A new list is added to the repository.

---

## [v1.0.3] - 2026-01-28

### Stable release

- Added:
  - Refined IDN/Punycode homograph rules and favicon tracking.
  - Expanded favicon whitelist to cover additional cases.
- Changes:
  - Synchronized `metadata.json` and list headers (version and last_updated).
  - Minor adjustments to exception rules and descriptions.
- Fixes:
  - Consolidated favicon rules to reduce potential conflicts.
  - Corrected minor formatting issues across lists.

---

## [v1.0.2] - 2026-01-20

### Hotfixes

- Added:
  - Expanded whitelist for IDN domains and favicons to reduce false positives.
  - GitHub Pages site as the official distribution channel.
  - Workflow-based validation for list syntax and rule consistency.
- Changes:
  - Refined filtering rules to improve reliability and compatibility.
  - Corrected minor syntax errors across lists.
  - Updated README.md, CONTRIBUTING.md, CHANGELOG.md and metadata.json .
  - Divided Standard list into engine-specific lists for ABP and Brave Shields.
- Fixes:
  - Minor breakage issues with secondary site features caused by over-blocking.

---

## [v1.0.1] - 2026-01-19

### Initial public release

- First public release of the **Security Filter Lists** repository.
- Introduced:
  - **IDN Homograph & Favicon Security List**  
    Available in uBlock Origin, ABP/Brave, and AdGuard formats.
- Established repository-wide design principles:
  - Security-focused scope
  - Conservative filtering
  - Long-term stability
  - Minimal false positives and site breakage
- Applied non-commercial, share-alike licensing (CC BY-NC-SA 4.0).
