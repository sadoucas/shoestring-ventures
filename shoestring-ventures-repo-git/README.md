# Shoestring Ventures

A business simulation game. Pick an industry, run its finances, sign contracts, and learn how a real business survives.

## Downloads
Every push to `main` runs the **Build apps** workflow (Actions tab). Open the latest run and download:
- **android**: `Shoestring-Ventures-debug.apk` (installable on Android), `Shoestring-Ventures-release.apk`, and `Shoestring-Ventures.aab` (for Google Play)
- **windows**: the NSIS installer `.exe`
- **ios**: an unsigned `.xcarchive`. An IPA needs your Apple signing certificate and provisioning profile.

## Structure
- `www/index.html`: the game (single file)
- `app/`: Electron shell for Windows
- `android/`, `ios/`: Capacitor native projects
