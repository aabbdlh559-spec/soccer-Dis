# SoccerStars Android Preview

The repository contains an Android APK build workflow. The source project archive is provided in the conversation as `SoccerStars-Android-Preview.zip`.

## Build from phone
1. Download the ZIP from the ChatGPT conversation.
2. In this repository, upload the ZIP file to the repository root (do not extract it; the workflow extracts it automatically).
3. Open the **Actions** tab.
4. Choose **Build SoccerStars Android APK** and tap **Run workflow**.
5. After the build completes, download the **SoccerStars-debug-APK** artifact.

The first Buildozer/python-for-android build has not yet been verified and may need dependency adjustments. The launcher skips the original menus and starts a local 2-player game.
