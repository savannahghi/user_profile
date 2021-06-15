# user_profile

`user_profile` is an open source project &mdash; it's one among many other shared libraries that make up the wider ecosystem of software made and open sourced by `Savannah Informatics Limited`.

It is a shared library between [BeWell-Consumer] and [BeWell-Professional] and is responsible for the user profile displayed on both apps and the associated actions that can be performed on Profile.

It is continuously maintained and updated by maintainers & reviewers

## Installation Instructions

Use this package as a library by depending on it

Run this command:

- With Flutter:

```dart
$ flutter pub add user_profile
```

This will add a line like this to your package's pubspec.yaml (and run an implicit dart pub get):

```dart
dependencies:
  user_profile: ^0.1.1
```

Alternatively, your editor might support flutter pub get. Check the docs for your editor to learn more.

Lastly:

Import it like so:

```dart
import 'package:user_profile/sil_contacts.dart';
```