# On IT 0.24.0-dev — LAN browser shortcut and subnet reference

Long-press a LAN device result to open its numeric IP in your browser. This works in current scans, saved scan details and comparisons. Ordinary taps still expand details. When a comparison shows an IP change, the later IP opens; Not seen results use the earlier IP. The initial URL is `http://<IP>/`.

Reference now includes an offline subnet-mask/CIDR guide with searchable `/0`–`/32` entries, total addresses, usable-host counts and `/31`–`/32` explanations. For example, `255.255.255.0` = `/24`: 256 total addresses, normally 254 usable hosts.

Download **on-it-0.24.0-dev.apk** below. Android 6.0/API 23 or later. Package `dev.itpro.app.debug`, version code 27, same development signer as previous previews. Existing preview users can install this as an update. A future Play build installs separately; use LAN backup/restore to transfer scans.

The build passed 252 automated host tests and Android debug/release lint with zero errors. Tests cover long-press versus tap, saved/comparison addresses, browser failure/retry, large text and invalid-address rejection. Device browser launch/return and the new reference guide still need phone validation. Opening the browser can stop a running scan when On IT goes into the background; partial results remain. Saved IPs may now refer to another device or network.

`SHA256SUMS.txt` contains asset checksums. This remains a development prerelease, not a Google Play production build. The auto-generated source archives contain only this downloads repository's documents.

[Privacy policy](https://on-it-privacy.pages.dev/) · Feedback: ripplystorm@gmail.com
