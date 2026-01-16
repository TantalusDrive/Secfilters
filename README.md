# Security Filter Lists
This repository hosts a small collection of **security-focused filter lists**, designed to mitigate **well-defined abuse and attack vectors** at the network and browser level that are not usually addressed in common security lists.

The lists published here are **not general-purpose adblocking or privacy lists**, they intentionally target **well-defined security threats** while prioritizing:

- long-term stability
- minimal false positives
- no site breakage

## Design principles 🎯
All lists in this repository follow the same core principles:

- **Security-first scope**  
  Only vectors with clear security or abuse implications are addressed.

- **Conservative filtering**  
  Rules are added only when they are demonstrably safe and broadly applicable.

- **Low churn / long-term usability**  
  Lists are designed to remain effective over time with minimal maintenance.

- **Explicit exceptions**  
  Verified brands, governments, and institutions are allowlisted where needed
  to avoid false positives.

## Available lists 📂
### IDN Homograph & Favicon Security List

Targets:

- **IDN / Punycode homograph attacks**  
  Prevents phishing and impersonation using visually confusable domain names.

- **Persistent favicon-based tracking**  
  Mitigates browser fingerprinting techniques abusing favicon cache behavior.

This list is a conceptual successor inspired by the work of DandelionSprout, while being independently maintained and curated.

## What this repository does not aim to do
This repository intentionally does **not** aim to:

- replace general-purpose adblocking lists or DNS filter lists
- block generic analytics, beacons, or advertising
- interfere with legitimate site functionality
- aggressively block content without clear security relevance

## Compatibility 🛠
Each list can be used independently and is compatible with:

- uBlock Origin
- AdGuard
- Brave Shields

## Attribution & inspiration
Some lists are conceptually inspired by existing community work. No content is copied, all lists are independently curated with distinct scope, structure, and maintenance philosophy.

## License ⚖️
This repository and its contents are released under the Creative Commons Attribution‑NonCommercial‑ShareAlike 4.0 International (CC BY‑NC‑SA 4.0) license.
