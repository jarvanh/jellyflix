⚠️ Please keep in mind, that Jellyflix development is in its early days. There are several (visual) bugs and many features missing. If you don't like the state of Jellyflix client right now, you can help improve it by contributing 😉.

---

# Jellyflix - Another Jellyfin client

Jellyflix is a cross platform Jellyfin Client for Desktop (Mac, Windows, Linux) and Mobile (iOS, Android). It aims to be a simple to use and reliable Jellyfin client for video content. It supports downloads (coming soon).

## Download

Supported platforms:
- iOS (Build it yourself)
- [Android](https://github.com/jellyflix-app/jellyflix/releases/latest/download/jellyflix.apk)
- macOS (Build it yourself)
- [Windows](https://github.com/jellyflix-app/jellyflix/releases/latest/download/jellyflix-windows.zip) (untested)
- [Linux](https://github.com/jellyflix-app/jellyflix/releases/latest/download/jellyflix-linux.zip) (untested)
- [Web](https://jellyflix.kiejon.com) (technically works, but it's only intended for demo usage)

I plan on releasing Jellyflix on the App Stores and Play Store in the future, when the app is stable enough.

## Contribute
Contributions are much appreciated. You can help the development by:
- opening issues/bug reports
- suggest features or give feedback
- translating the app
- contributing with pull requests

## Build
Jellyflix is developed in Flutter a cross-platform framework. The programming language is Dart, which is quite easy to learn. <br>
To build the project you need Flutter [installed](https://docs.flutter.dev/get-started/install) and at least one supported device/emulator to run the project on. <br>
Then clone the repository and run the following commands.
```
cd jellyflix
flutter clean
flutter pub get
flutter run
```

## Linux
If you want to build Jellyflix for Linux you need some additional dependencies: `libmpv-dev, mpv, libsecret-1-dev, libjsoncpp-dev

## Privacy
Jellyflix doesn't collect data and doesn't send data to third parties.

## License
Jellyflix is licensed under [GPLv3](LICENSE).

The Jellyflix logo is licensed under [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) and is a remix of the original [Jellyfin icon](https://github.com/jellyfin/jellyfin-ux/blob/master/branding/SVG/icon-transparent.svg) by the [Jellyfin Project](https://jellyfin.org/) which is licensed under [CC-BY-SA 4.0](https://github.com/jellyfin/jellyfin-ux/blob/master/LICENSE)