# SpaceSonar Pro – downloads and issue tracker

This repository carries the releases of SpaceSonar Pro for Windows: the
installer, the portable ZIP and the update feed. The source code does not
live here. About the app, in German: https://appsonar.de/apps/spacesonar-pro.html

## Download

The latest version is under "Releases" with two files:

- `SpaceSonarPro_<version>_x64-setup.exe` – installer for the current user,
  no administrator rights needed.
- `SpaceSonarPro_<version>_x64-portable.zip` – runs without installation:
  unpack and start `SpaceSonarPro.exe`.

The files are not signed with a certificate, so Windows SmartScreen shows a
warning on the first start; "More info" and "Run anyway" start the app.

## Updates

The app never goes online on its own. It looks for a newer version only when
you click "Check for updates" in its settings; it then reads `latest.json` of
the latest release here.

## Reporting a problem

Bugs and requests go in as issues of this repository. Issues are public: do
not include personal data, file names that reveal something about you, or
screenshots with such content.

The easiest way is "Report a problem" in the app: it writes a short text and
a bundle with the log, the settings and the machine facts, with file paths
redacted. "Open an issue" brings you here with the text filled in; attach the
bundle by dragging it from the Explorer into the issue.

## Licence

The current version of SpaceSonar Pro is free to use, privately and at work.
The usage licence ships with every version (`LICENSE.txt` in the ZIP and in
the program folder); the text is also here in `LICENSE`.

## Deutsch

Beschreibung, Download und Datenschutzerklärung auf Deutsch:
https://appsonar.de/apps/spacesonar-pro.html. Issues dürfen auf Deutsch oder
Englisch geschrieben werden.
