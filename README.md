# Security Filter Lists
> Addressing edge-case abuse vectors often overlooked by mainstream filter lists.

This repository hosts a small collection of lists designed to mitigate **security edge cases** at the network and browser level.
<br>The lists published here are **not general-purpose adblocking or privacy lists**, they intentionally target **well-defined security threats**, while prioritizing:

- long-term stability
- minimal false positives
- no site breakage

---

## Design principles
These apply to all lists in this repository:

  **Security-first scope**  
  Only vectors with clear security or abuse implications are addressed.

  **Conservative filtering**  
  Rules are added only when they are demonstrably safe, reproducible, and do not cause documented site breakage.

  **Low churn / long-term usability**  
  Lists are designed to remain effective over time with minimal maintenance.

  **Explicit exceptions**  
  Verified brands, governments, and institutions are allowlisted where needed to avoid false positives.

## Available lists
### IDN Homograph & Favicon Security List

Targets:

- **[IDN / Punycode homograph attacks](https://en.wikipedia.org/wiki/IDN_homograph_attack)**  
  Prevents phishing and impersonation using visually confusable domain names.

- **Persistent [favicon-based tracking](https://www.ghacks.net/2021/01/22/favicons-may-be-used-to-track-users/)**  
  Mitigates browser fingerprinting techniques abusing favicon cache behavior.

  This list is a conceptual successor inspired by the work of [DandelionSprout](https://github.com/DandelionSprout), while being independently maintained and curated.

**(Additional lists coming soon)**



## What this repository does NOT aim to do

- replace general-purpose adblocking lists or DNS filter lists
- block generic analytics, beacons, or advertising
- interfere with legitimate site functionality
- aggressively block content without clear security relevance

## Compatibility
Each list can be used independently and is compatible with [uBlock Origin](https://ublockorigin.com/), [AdGuard](https://adguard.com/it/adguard-browser-extension/overview.html), [Brave Shields](https://brave.com/shields/) and [AdBlock Plus](https://adblockplus.org/).

## Attribution & inspiration
Some lists are conceptually inspired by existing community work. No content is copied, all lists are independently curated with distinct scope, structure, and maintenance philosophy.

## License
This repository and its contents are released under the Creative Commons Attribution‑NonCommercial‑ShareAlike 4.0 International ([CC BY‑NC‑SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)) license.
