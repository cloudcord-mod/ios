<div align="center">

<img src="https://raw.githubusercontent.com/cloudcord-mod/release-hub/main/assets/cloudcord-logo.png" width="250" alt="CloudCord logo">

# CloudCord iOS

**The iOS and iPadOS loader and the shared mobile runtime.**

[**Downloads**](https://getcloudcord.com/#download) · [**Release Hub**](https://github.com/cloudcord-mod/release-hub) · [**Builds**](https://github.com/cloudcord-mod/ios/actions) · [**Status**](https://getcloudcord.com/status)

</div>

---

## Install

1. Download the [CloudCord IPA](https://getcloudcord.com/download/ios).
2. Sign and sideload it with a compatible tool.
3. Open Discord and look for **CloudCord** in settings. Profile and Add-ons are available on supported builds.

For signing or startup issues, include the iOS version, signing tool, Discord build, and exact error in your [bug report](https://github.com/cloudcord-mod/release-hub/issues).

## What ships here

| Path | Purpose |
| --- | --- |
| [`ios/native-ios/`](ios/native-ios) | Native loader, bridge, and packaging inputs |
| [`ios/runtime/`](ios/runtime) | Shared Android and iOS JavaScript runtime |
| [`ios/scripts/`](ios/scripts) | Runtime checks and packaging utilities |

The [mobile workflow](.github/workflows/build.yml) builds and tests the shared runtime. Release Hub handles the public runtime and IPA releases. The [Android repository](https://github.com/cloudcord-mod/android) owns the Manager and patcher.

[Source and history before the repository split](https://github.com/cloudcord-mod/release-hub/commit/69bdb299aad1032b898a8d2904d9024b52721349).

## Credits and license

CloudCord is maintained by [Xohus](https://xohus.lol/). The runtime builds on Vendetta, Bunny, and [Kettu](https://codeberg.org/cocobo1/Kettu). The native loader is based on [RainTweak](https://codeberg.org/raincord/RainTweak). [Mobile credits](ios/docs/CREDITS.md) · [RainTweak notice](ios/native-ios/RAIN-NOTICE.md) · [Loader OSL license](ios/native-ios/RAIN-LICENSE) · [Runtime BSD license](ios/runtime/LICENSE)
