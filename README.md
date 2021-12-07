# icon_background_issue

to reproduce:

- run `flutter pub run flutter_launcher_icons:main`
- run `flutter run --release` on *android 12 device*

observe inconsistent icon background 

- in pubspec `#000000`
- in launcher `#ffffff`
- minimized "blue"