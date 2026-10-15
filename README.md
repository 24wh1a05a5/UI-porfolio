# Prasanna Miyapuram Portfolio

A responsive Flutter portfolio with editable resume cards, education and
highlight timelines, contact links, and locally saved edits.

## Requirements

- Flutter SDK (stable) with Dart included
- An emulator, connected device, or desktop target enabled for Flutter

## Run

Install Flutter from the official Flutter website and add its `bin` directory
to `PATH`. This source folder was not generated with platform runner files, so
create the platform scaffolding once from the project directory:

```powershell
flutter create --platforms=web,windows,android .
flutter pub get
flutter run -d chrome
```

To run on another connected device, use `flutter devices` and replace `chrome`
with its device ID. Validate the project with:

```powershell
flutter analyze
flutter test
```

To create a web build, run `flutter build web`.

For VS Code, install the **Flutter** extension (it also installs the **Dart**
extension) and select the Flutter SDK when prompted. These editor extensions
do not replace the Flutter SDK itself.

## Personalize

- Replace the placeholder email from the **Contact** tab using its edit icon.
- Tap any resume or project card (or its edit icon) to update its text. Changes
  are saved locally on the device.
- Copy an optional profile photo to `assets/images/profile.png`. The hero
  displays it automatically and falls back to initials when it is missing.
- Certificate artwork is optional; the resume currently lists the provided
  certification names without inventing certificate images or awards.
