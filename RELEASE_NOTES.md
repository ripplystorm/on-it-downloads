# On IT 0.21.0-dev — Android preview

The full Android networking toolkit is available as a free development preview.

- LAN scans with live devices, saved history, comparisons, filters and sorting on one tab.
- Scan/comparison text and CSV exports, manual JSON backup/restore, and diagnostic copy/share reports.
- Ping, traceroute, DNS, TCP ports, WHOIS/RDAP, Wi-Fi and Bluetooth tools.
- Optional Cloudflare speed test and offline references with T568B as the standard.
- On IT cape icon, descriptive title, dark/light themes, separate Settings → Support and offline privacy policy.

**Install:** Download `on-it-0.21.0-dev.apk` under Assets. Requires Android 6.0/API 23 or later. `SHA256SUMS.txt` contains the file checksum.

**Preview status:** This is the tested development APK, package `dev.itpro.app.debug`, version code 23. It uses development signing and is not a Google Play production build. A future Play build will install separately; back up saved LAN scans for transfer. Support payments remain disabled.

**Validation:** The existing APK checkpoint passed 240 automated tests and Android lint with zero errors. Users reported successful testing on several devices. Broader device/version and accessibility checks remain in progress.

**Privacy:** No app analytics or automatic crash-reporting SDKs. The Cloudflare panel has a separate provider-data disclosure before loading. [Read the privacy policy](https://on-it-privacy.pages.dev/).

**Feedback:** [ripplystorm@gmail.com](mailto:ripplystorm@gmail.com). Include Android/device/app versions and reproduction steps; remove private network data from any shared reports.
