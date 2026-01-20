# Changelog

This document tracks meaningful, user-relevant events in the repository lifecycle.<br>
We follow an event-based versioning approach: only changes that affect security scope, threat models, or list availability are recorded. Minor rule tuning, exception adjustments, or formatting refactors are not included.

### Future versions

Updates will only be recorded when:
- A new class of security abuse is addressed.  
- The scope or philosophy of an existing list changes.  
- A new list is added to the repository.

---

## [v1.0.2] - 2026-01-20

### Hotfixes

- Added:
  - Expanded whitelist for IDN domains and favicons to reduce false positives.
  - GitHub Pages site as the official distribution channel.
  - Workflow-based validation for list syntax and rule consistency.
- Changed:
  - Refined filtering rules to improve reliability and compatibility.
  - Corrected minor syntax errors across lists.
  - Updated README.md, CONTRIBUTING.md, CHANGELOG.md and metadata.json .
- Fixed:
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
