# Linux Freedom

A free, open-source Linux environment builder for Android. No subscriptions, no ads, no accounts.

## Status: Phase 1 (selection screens only)

- Distribution picker (9 options) and desktop picker (10 options). Everything is unlocked.
- Your choices are saved on the device.
- Nothing is downloaded or installed yet. Those arrive in Phases 2 to 4.

## Build the APK with GitHub Actions

1. Create a new GitHub repository and upload this project's files. Uploading from a computer browser is much easier than from a phone.
2. Open the Actions tab. "Build debug APK" runs on every push.
3. Open the finished run and download the `linux-freedom-debug-apk` artifact.
4. Copy the APK to your device and install it. If Android asks, allow installs from the app you opened it with (browser or file manager).

The workflow generates the Gradle wrapper itself. To commit the wrapper, run `gradle wrapper --gradle-version 8.7` once on a computer.

## Requirements

Android 8.0 (API 26) or newer. Phase 1 needs no special permissions.

## Known limits

- Storage and RAM are shown as tiers (None, Light, Medium, Heavy). Numbers come after device testing.
- Distribution and desktop support is not verified yet. Official download sources are checked in Phase 2.

## License

Not chosen yet. Pick one (for example MIT or GPL-3.0) before making the repository public.
