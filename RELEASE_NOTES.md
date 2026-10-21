# On IT for Windows 0.36.0 — Desktop preview

On IT brings connection information, network diagnostics, LAN discovery and saved scans, wireless tools and offline references together on Windows.

## New in 0.36

- **Launch On IT** is checked by default on the installer's Finish page. Leave it checked to open the installed app, or clear it to finish without opening.
- Includes the Speed Test Start fix: the provider's verification frame can now load normally. Speed Test was confirmed working in manual use.
- Includes visible overflow scrollbars, Matrix and Crow themes, the corrected taskbar icon, and browser buttons for current and saved LAN results.

## Download and install

Choose **on-it-windows-0.36.0-preview.exe** for normal setup, or the MSI as an alternative. Close an existing installed copy normally before upgrading. Use the portable ZIP if you prefer to extract a complete folder and run `On IT/On IT.exe` without installation. Keep the extracted app and runtime folders together.

This is a Windows x64 preview. Java and the helper runtime are included; PowerShell is not required. Speed Test needs Microsoft Edge WebView2 Runtime. Wireless features depend on hardware and Windows access. Coverage across Windows versions and hardware remains limited.

The Windows setup installs for the current user. Saved scans are stored separately from the program folder; back them up before updates. See `WINDOWS_USER_GUIDE.md` for instructions.

## Validation and current limits

The app and both installers built successfully. Focused installer configuration checks passed. An actual 0.35 → 0.36 upgrade was confirmed, including all common installed file hashes and retained saved-scan/settings data. The tester confirmed that leaving Launch On IT checked and clicking Finish opened the app automatically. Broad regression and platform acceptance were not repeated for this preview.

**This preview is unsigned.** Windows or antivirus software may warn or block it. Keep security protection enabled and report the detection details rather than adding exclusions. No antivirus clearance is claimed.

`SHA256SUMS.txt` lists the selected public download checksums. The automatically generated Source code archives contain this downloads repository's documents.

## Privacy and feedback

Saved scans remain local unless you export or back them up. Diagnostics contact the destinations you choose. Speed Test loads Cloudflare only after agreement; that provider and the Windows WebView2 runtime have their own data handling. Settings → Privacy includes the Windows-specific details and provider links. Optional support opens a separate Stripe checkout.

Feedback: ripplystorm@gmail.com. Include the app/Windows versions and steps to reproduce; redact private network details from screenshots and reports.

---

# On IT 0.24.0-dev — LAN browser shortcut and subnet reference

Long-press a LAN device result to open its numeric IP in your browser. This works in current scans, saved scan details and comparisons. Ordinary taps still expand details. When a comparison shows an IP change, the later IP opens; Not seen results use the earlier IP. The initial URL is `http://<IP>/`.

Reference now includes an offline subnet-mask/CIDR guide with searchable `/0`–`/32` entries, total addresses, usable-host counts and `/31`–`/32` explanations. For example, `255.255.255.0` = `/24`: 256 total addresses, normally 254 usable hosts.

Download **on-it-0.24.0-dev.apk** below. Android 6.0/API 23 or later. Package `dev.itpro.app.debug`, version code 27, same development signer as previous previews. Existing preview users can install this as an update. A future Play build installs separately; use LAN backup/restore to transfer scans.

The build passed 252 automated host tests and Android debug/release lint with zero errors. Tests cover long-press versus tap, saved/comparison addresses, browser failure/retry, large text and invalid-address rejection. Device browser launch/return and the new reference guide still need phone validation. Opening the browser can stop a running scan when On IT goes into the background; partial results remain. Saved IPs may now refer to another device or network.

`SHA256SUMS.txt` contains asset checksums. This remains a development prerelease, not a Google Play production build. The auto-generated source archives contain only this downloads repository's documents.

[Privacy policy](https://on-it-privacy.pages.dev/) · Feedback: ripplystorm@gmail.com
