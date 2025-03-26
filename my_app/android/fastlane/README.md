fastlane documentation
----

# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```sh
xcode-select --install
```

For _fastlane_ installation instructions, see [Installing _fastlane_](https://docs.fastlane.tools/#installing-fastlane)

# Available Actions

## Android

### android test

```sh
[bundle exec] fastlane android test
```

Runs unit tests

### android build

```sh
[bundle exec] fastlane android build
```

Builds the app as an AAB bundle

### android bump_version

```sh
[bundle exec] fastlane android bump_version
```

Increments version code and name

### android beta

```sh
[bundle exec] fastlane android beta
```

Builds and uploads the AAB to the Play Store Beta track

### android deploy

```sh
[bundle exec] fastlane android deploy
```

Deploy a new production version to Google Play

----

This README.md is auto-generated and will be re-generated every time [_fastlane_](https://fastlane.tools) is run.

More information about _fastlane_ can be found on [fastlane.tools](https://fastlane.tools).

The documentation of _fastlane_ can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
