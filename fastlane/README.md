fastlane documentation
----

# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```sh
xcode-select --install
```

For _fastlane_ installation instructions, see [Installing _fastlane_](https://docs.fastlane.tools/#installing-fastlane)

# Available Actions

### environments

```sh
[bundle exec] fastlane environments
```

Cloning the environment and keystore files into the local machine

### sync_environments

```sh
[bundle exec] fastlane sync_environments
```

Sync the environment and keystore files to the repository

### google_services

```sh
[bundle exec] fastlane google_services
```

Downloading and installing the google services files...

----


## iOS

### ios certificates

```sh
[bundle exec] fastlane ios certificates
```

Install the certificates into the local machine

### ios release_beta

```sh
[bundle exec] fastlane ios release_beta
```

Push a new beta build to TestFlight

### ios release_testflight

```sh
[bundle exec] fastlane ios release_testflight
```

Push a new beta build to Testflight

----


## Android

### android build_apk

```sh
[bundle exec] fastlane android build_apk
```

Build release apk file

### android build_aab

```sh
[bundle exec] fastlane android build_aab
```

Build release aab file

### android release_beta

```sh
[bundle exec] fastlane android release_beta
```

Push a new Beta build to Firebase Distribution

### android release_store

```sh
[bundle exec] fastlane android release_store
```

Push a new Production build to Firebase Distribution & Google Play

----

This README.md is auto-generated and will be re-generated every time [_fastlane_](https://fastlane.tools) is run.

More information about _fastlane_ can be found on [fastlane.tools](https://fastlane.tools).

The documentation of _fastlane_ can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
