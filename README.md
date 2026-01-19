# Security Filter Lists
> Addressing niche but reproducible security abuse vectors often underrepresented in mainstream filter lists.

This repository hosts a small set of filter lists targeting specific security abuse vectors at the network and browser level.

They are not intended for general-purpose adblocking or privacy use. The focus is on well-defined threats, with an emphasis on stability and avoiding site breakage.

## Design principles

**Security-first scope**  
Only vectors with clear security implications are addressed.

**Conservative filtering**  
Rules are added only when reproducible and demonstrably safe.

**Low churn**  
Lists are designed to remain effective over time with minimal maintenance.

**Explicit exceptions**  
Allowlisting is used where required to avoid false positives.

## Compatibility

- Brave Shields and AdBlock Plus should use the **Standard** lists.
- uBlock Origin and AdGuard should use their **engine-specific** variants.

## What this repository does not aim to do

- replace general-purpose adblocking or DNS filter lists
- block generic analytics, advertising, or trackers
- interfere with legitimate site functionality
- apply speculative or aggressive filtering

---

## Available lists

### IDN Homograph & Favicon Security List

This list is conceptually inspired by the work of [DandelionSprout](https://github.com/DandelionSprout), while being independently curated, structured, and maintained.

**Targets**:

- **[IDN / Punycode homograph attacks](https://en.wikipedia.org/wiki/IDN_homograph_attack)**  
  Mitigates phishing and impersonation via visually confusable internationalized domain names.

- **Persistent [favicon-based tracking](https://www.ghacks.net/2021/01/22/favicons-may-be-used-to-track-users/)**  
  Reduces fingerprinting techniques abusing favicon cache persistence.

>**URLs**
>
>- **Standard (Brave Shields / ABP):**
>  https://tantalusdrive.github.io/Secfilters/Lists/Standard/IDNHomographFavicon.txt
>
>- **uBlock Origin:**  
>  https://tantalusdrive.github.io/Secfilters/Lists/uBlock/IDNHomographFavicon.txt
>
>- **AdGuard:**  
>  https://tantalusdrive.github.io/Secfilters/Lists/AdGuard/IDNHomographFavicon.txt

---

## Attribution & inspiration

Some lists are conceptually inspired by existing community work. No content is copied; all lists are independently curated with a distinct scope and maintenance philosophy.

## License

This repository and its contents are released under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International ([CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0)).
