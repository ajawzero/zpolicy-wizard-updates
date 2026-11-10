# zPolicy Wizard updates

The update feed and downloads for zPolicy Wizard on the Mac, an app for Zscaler that builds best-practice configuration (ZIA, Private Access, Digital Experience, Client Connector and AI Guard), shows exactly what it would change before changing anything, and simulates what your policy does to traffic. This repository holds no source code.

zPolicy Wizard isn't an official Zscaler tool: it was built by a Zscaler SE to help SEs and Zscaler practitioners. Its content builds on ZeroTrustPanda's ZTP Policy Wizard and Policy Simulator, with the author's permission. On Windows, it comes from the Microsoft Store.

- **Nothing is released here yet.** The first release will be zPolicy Wizard 4.0. Until then, the Mac app is Zscaler Policy Wizard 3.4, from [its own updates page](https://github.com/ajawzero/zscaler-policy-wizard-mac-updates).
- `appcast.xml` (to be served at https://ajawzero.github.io/zpolicy-wizard-updates/appcast.xml) will be the signed list of versions that zPolicy Wizard checks for updates.
- Each release will have that version's DMG and its release notes. The list and each download are signed with zPolicy Wizard's own update key, and each DMG with Developer ID and notarized by Apple; the app checks the signatures before installing.
