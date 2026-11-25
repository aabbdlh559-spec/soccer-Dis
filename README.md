# SoccerStars Android Preview

This repository has a GitHub Actions workflow to package the standalone Pygame preview into a debug APK.

## Build from phone
1. Download `SoccerStars-Android-Preview-Fixed.zip` from the ChatGPT conversation.
2. Rename it to `SoccerStars-Android-Preview.zip` and upload it to the repository root. Do not extract it; the workflow extracts the archive.
3. Open the **Actions** tab.
4. Run **Build SoccerStars Android APK**.
5. When the workflow succeeds, download the `SoccerStars-debug-APK` artifact.

The workflow validates the archive before building and reports a clear error if the archive or required assets are missing. The APK build itself has not yet been verified on GitHub Actions; any later Buildozer/Android packaging errors will be visible in the build logs.
