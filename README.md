# OptiFlix updates

Official Windows app releases for OptiFlix, a player for your own IPTV sources.

Download the installer from the Releases page. Connect your own Xtream Codes or M3U playlist after installation. This repository does not provide television streams or subscriptions.

## OptiFlix 1.0.0

The official version series now starts at 1.0.0. Existing 4.x users must install 1.0.0 manually once; older apps compare version numbers and cannot offer 1.0.0 as a newer update. Saved libraries and history are preserved.

The app checks `stable.json` shortly after launch and every six hours while open. Available app updates show an in-app notification, update icon, and NEW badge. Notices wait until playback closes. Users choose when to download and install.

For future 1.x releases, publish the installer first, then update `stable.json` with its version, URL, SHA-256 checksum, and release notes. The old `latest.json` is retained only for legacy 4.x clients.
