# Security Filter Lists
> Addressing niche but reproducible **security abuse vectors** often underrepresented in mainstream filter lists.

This repository hosts a small set of filter lists targeting specific security abuse vectors at the network and browser level.

They are not meant for general-purpose adblocking or privacy use. In practice, they focus on well-defined threats, prioritizing stability, minimal false positives, and avoiding site breakage.

## Design principles

**Security-first scope**  
We address only vectors with clear, reproducible security implications. Each rule is added deliberately to mitigate actual threats.

**Conservative filtering**  
Rules are included only when demonstrably safe. We avoid speculative or aggressive filtering that could disrupt legitimate site functionality.

**Low churn**  
Lists are designed to remain effective over time, requiring minimal maintenance. Updates occur only when security risks evolve or new edge cases are discovered.

**Explicit exceptions**  
Major brands, governments, and institutions are deliberately allowlisted to prevent false positives or critical login issues.

## Compatibility

- Each adblocker (ABP, AdGuard, Brave Shields, uBlock Origin) should use their **engine-specific** variant.
- **Do not combine lists for different engines**; subscribe only to the list matching your setup.

## What this repository does not aim to do

- Replace general-purpose adblocking or DNS filter lists.  
- Block generic analytics, advertising, or trackers.  
- Interfere with legitimate site functionality.  
- Apply speculative or aggressive filtering without clear security justification.

---

## Available lists

### IDN Homograph & Favicon Security List

This list is conceptually inspired by the work of [DandelionSprout](https://github.com/DandelionSprout), while remaining independently curated, structured, and maintained.

**Targets**:

- **[IDN / Punycode homograph attacks](https://en.wikipedia.org/wiki/IDN_homograph_attack)**  
  Prevents phishing and impersonation using visually confusable internationalized domain names.  

- **Persistent [favicon abuse](https://www.ghacks.net/2021/01/22/favicons-may-be-used-to-track-users/)**  
  Prevents security risks from favicon caching, such as spoofing, phishing, and malicious tracking vectors.

>**Subscription URLs**
>- **ABP:** https://tantalusdrive.github.io/Secfilters/Lists/ABP/IDNHomographFavicon.txt
>
>- **Brave Shields:** https://tantalusdrive.github.io/Secfilters/Lists/Brave/IDNHomographFavicon.txt
>
>- **uBlock Origin:** https://tantalusdrive.github.io/Secfilters/Lists/uBlock/IDNHomographFavicon.txt
>
>- **AdGuard:** https://tantalusdrive.github.io/Secfilters/Lists/AdGuard/IDNHomographFavicon.txt
>
> Raw GitHub URLs are available only as fallback.

---

## Attribution & inspiration

Some lists are conceptually inspired by community work. No content is copied; all rules are independently curated, with distinct scope and maintenance philosophy.

## License

![CC BY-NC-SA 4.0](https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png)  
This repository and its contents are released under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International ([CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0)).
