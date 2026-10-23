# Anivora Android releases

This repository hosts official signed Anivora Android APKs, checksums, update metadata and release notes. The application source repository remains private. No Expo, Android or backend source is published here.

[Download the latest APK](https://github.com/brandon-300/Anivora-Releases/releases/latest)

Open the latest release, expand **Assets**, and download its `anivora-…-arm64.apk`. No GitHub login is needed. Install it over your existing Anivora installation; do not uninstall or clear your data. Android may ask you to allow your browser to install apps. The package remains `com.brandon300.anivora` and official updates use the existing signing certificate.

Older builds check for updates through Render. If that service is unavailable, manually install the newest APK here once. Builds using the public updater then check `latest.json` and download APKs directly from GitHub's CDN, independently of Render. You can jump directly to the latest version; intermediate APKs are unnecessary. Auth, library sync and comments still require the backend.

Each release includes a `SHA256SUMS.txt` file and a `latest.json` metadata snapshot. The stable feed is https://raw.githubusercontent.com/brandon-300/Anivora-Releases/main/latest.json. Only the private source repository's verified release process advances this feed.

Official signing certificate SHA-256:

```text
fac61745dc0903786fb9ede62a962b399f7348f0bb6f899b8332667591033b9c
```

APKs are distributed for sideloading. Keep Android's installation protections enabled, and verify that downloads come from this repository. This repository does not grant a license to the private application source or to third-party media.
