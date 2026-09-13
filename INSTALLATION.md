# Windows beta installation

[Download Lane Desktop 0.3.4](https://github.com/Bleuszz/lane-public/releases/download/v0.3.4-rc.1/Lane-Setup-0.3.4.exe). Windows 10/11, x64. This is an unsigned beta, not a stable or fully physically verified release. Windows may display an unknown-publisher warning; inspect the source and checksum rather than bypassing unexpected security warnings.

1. Download the installer linked above and compare SHA-256 with CHECKSUMS.md.
2. Close Lane, install the beta, then open Lane.
3. Use https://lane-staging.onrender.com as the Lane website and sign into your existing Lane account. Approve the device in the browser.
4. Connect a marketplace by signing in directly to it. Complete any legitimate verification yourself.
5. Restart Lane and check pairing/session recovery. Revoke the device from the website and confirm cloud access stops.
6. Test an upgrade without clearing app data. To uninstall, use Windows Settings > Apps. Uninstall preserves app data; explicitly disconnect marketplace sessions first if you intend to remove them.

Choose Import all listings to read the discovered wardrobe into the paired Lane account. Use Retry unfinished items for failed or interrupted reads. Follow each item’s result in Desktop.

Keep original product photos. Photos remain marketplace-hosted references. Full real Vinted import acceptance still needs owner reauthentication; no reliable fully automated publishing claim is made. Report issues to LaneListing@proton.me; never send cookies, tokens or passwords.

macOS is planned next; Linux later. No builds for either exist yet.

Windows 0.3.4 installer execution and app launch have been exercised on Windows; complete marketplace, upgrade and uninstall/reinstall acceptance is still pending. The local encrypted fixture survived a process restart.
