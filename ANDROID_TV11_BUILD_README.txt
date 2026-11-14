RING RACERS 2.4 — ANDROID TV 11 BUILD SOURCE
===========================================

This is a source package, not an APK.

Android TV adjustments included:
- Android TV (Leanback) is declared as an optional device feature.
- MainActivity is listed as a Leanback launcher.
- Touch-control overlays are disabled on devices reporting FEATURE_LEANBACK.
- Touchscreen remains optional so TV devices can install the app.

Build automation:
- GitHub Actions workflow: .github/workflows/android.yml
- Push the source to branch: android-fixes-v6
- Or run the workflow manually from GitHub Actions.
- Expected artifacts: RingRacers-android-arm64 and RingRacers-android-arm32.

The workflow has not been executed in this package-generation environment.
A successful GitHub Actions run is required before an APK exists.
The ARM64 artifact is normally the first one to try on a modern Android TV;
use ARM32 only if the TV's system is 32-bit.

The workflow downloads the official Ring Racers v2.4 assets during the build.
Do not upload copyrighted game asset bundles to the source repository.
