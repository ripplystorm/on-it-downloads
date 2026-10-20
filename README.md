# On IT – Networking Tools

Android networking tools from **Ripply Apps**. Free to use, with no ads or app analytics SDK.

## Download

Open [Releases](https://github.com/ripplystorm/on-it-downloads/releases) and choose **On IT 0.24.0-dev — LAN browser shortcut and subnet reference**. Under Assets, download `on-it-0.24.0-dev.apk`. The automatically generated Source code downloads contain this downloads repository's documents.

This is a development preview for Android 6.0 or later. It uses package `dev.itpro.app.debug` and development signing. A future Google Play build will install separately; use LAN → Back up saved scans to keep a portable copy of your scans.

## Install or update

1. Download the APK from this repository's release.
2. Open it on your Android device and follow Android's installation prompts. If prompted, allow installation from the browser or file app you used. You can turn that permission off afterward; keep Play Protect enabled.
3. Existing testers can install this over the previous On IT development build signed by Ripply Apps. Back up saved scans first. If Android reports a signing conflict, report it before uninstalling, because uninstalling deletes local app data.

## New in this preview

- Long-press a LAN device to open its IP in your browser, from current results, saved scans or comparisons. Normal taps still expand details. Comparisons use the later IP when it changed; Not seen rows use the earlier IP. The initial URL is `http://<IP>/`.
- Offline subnet-mask/CIDR lookup in Reference: `/0` through `/32`, total addresses, conventional usable hosts, and explicit `/31` and `/32` explanations. Search by mask or prefix; `255.255.255.0` shows `/24`, 256 addresses and normally 254 hosts.

Opening the browser can background On IT and stop a running scan, retaining its partial results. Saved addresses may now refer to a different device or network. Device web interfaces and HTTPS redirects depend on the device and browser.

## Included tools

- Connection information and LAN scan/save/compare, with difference filters and sorting.
- Text/CSV exports and manual JSON backup/restore of saved LAN scans.
- Ping, traceroute, DNS lookup, TCP port checks and WHOIS/RDAP.
- Wi-Fi discovery/channel overlap and Bluetooth discovery.
- Optional Cloudflare hosted speed test, loaded only when requested.
- Offline Ethernet wiring, subnet, DNS and command references; T568B is the standard/default.
- Dark/light/system themes and separate Settings sections.

Availability depends on Android permissions, hardware and the network. LAN results are observations rather than a complete device inventory. Optional one-time support is available in Settings → Support through external Stripe checkout. Choose your amount there; checkout starts at USD $1. Contributions unlock no features.

## Validation, privacy and feedback

The build passed 252 automated host tests and Android debug/release lint with zero errors. Actual browser launch/return and the new subnet guide still need phone validation. This is a development prerelease, not a Google Play production build.

Saved LAN scans stay on the device unless you explicitly export or back them up. No app analytics or automatic crash-reporting SDK is included. Diagnostics contact their selected destinations. Optional Cloudflare and Stripe processing is described in the policy.

[Privacy policy](https://on-it-privacy.pages.dev/) · [Email Ripply Apps](mailto:ripplystorm@gmail.com)

For feedback, include the app version, Android version, device model and steps to reproduce. Redact network addresses, device names and other private details from reports.
