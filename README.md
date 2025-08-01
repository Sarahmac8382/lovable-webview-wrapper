
# Lovable WebView Wrapper

This project wraps your Lovable app URL (https://farmnotes.lovable.app/login) in a native Android WebView.

## Features
- Loads your Lovable app in a WebView
- GitHub Actions workflow to build APK automatically
- Placeholder for Fastlane setup

## Fastlane Setup (Optional)
To automate Google Play deployment:
1. Install Fastlane: `fastlane init`
2. Configure `supply` with your Play Console JSON key
3. Store credentials in GitHub Secrets:
   - `GOOGLE_PLAY_JSON_KEY`
   - `KEYSTORE_PASSWORD`
   - `KEY_ALIAS`
   - `KEY_PASSWORD`

Extend `.github/workflows/android-build.yml` with Fastlane steps.

