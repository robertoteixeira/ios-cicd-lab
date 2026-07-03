fastlane documentation
----

# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```sh
xcode-select --install
```

For _fastlane_ installation instructions, see [Installing _fastlane_](https://docs.fastlane.tools/#installing-fastlane)

# Available Actions

## iOS

### ios ci_build

```sh
[bundle exec] fastlane ios ci_build
```

Prepare and build app in CI

### ios ci_test

```sh
[bundle exec] fastlane ios ci_test
```

Run tests in CI

### ios build

```sh
[bundle exec] fastlane ios build
```

Build the iOS app for simulator

### ios increment_build

```sh
[bundle exec] fastlane ios increment_build
```

Increment the iOS build number

### ios set_ci_build_number

```sh
[bundle exec] fastlane ios set_ci_build_number
```

Set build number from CI

### ios test

```sh
[bundle exec] fastlane ios test
```

Run iOS tests

### ios archive

```sh
[bundle exec] fastlane ios archive
```

Archive the iOS app

### ios version_info

```sh
[bundle exec] fastlane ios version_info
```

Print the current app version and build number

### ios set_version

```sh
[bundle exec] fastlane ios set_version
```

Set the marketing version

----

This README.md is auto-generated and will be re-generated every time [_fastlane_](https://fastlane.tools) is run.

More information about _fastlane_ can be found on [fastlane.tools](https://fastlane.tools).

The documentation of _fastlane_ can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
