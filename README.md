# RadWeave Capture releases

Official Windows installers for **RadWeave Capture** (https://radweave.ai). This repository holds release binaries only; the application source is private.

* `RadWeaveCapture-vX-Setup.exe` – per-user Windows installer (no administrator rights).
* `latest.json` – the signed update manifest read by RadWeave Capture's built-in update check. It is signed with a release key whose public half is built into the application; the installer's size and SHA-256 are taken from the signed data.

The installers are **not yet Authenticode code-signed**, so Windows may show an "unknown publisher" or SmartScreen notice. Verify a download against the SHA-256 in the release notes.
