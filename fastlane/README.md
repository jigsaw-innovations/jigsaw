fastlane documentation
----

# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```sh
xcode-select --install
```

For _fastlane_ installation instructions, see [Installing _fastlane_](https://docs.fastlane.tools/#installing-fastlane)

# Available Actions

### liftoff

```sh
[bundle exec] fastlane liftoff
```



### generate_push_certificate

```sh
[bundle exec] fastlane generate_push_certificate
```



### generate_keystore

```sh
[bundle exec] fastlane generate_keystore
```



### update_version

```sh
[bundle exec] fastlane update_version
```



### prepare_icons

```sh
[bundle exec] fastlane prepare_icons
```



### discard_icons

```sh
[bundle exec] fastlane discard_icons
```



----


## iOS

### ios build_application

```sh
[bundle exec] fastlane ios build_application
```



### ios suffix_name

```sh
[bundle exec] fastlane ios suffix_name
```



### ios fetch_profiles

```sh
[bundle exec] fastlane ios fetch_profiles
```



### ios develop

```sh
[bundle exec] fastlane ios develop
```

Local development using iOS Simulator...

### ios staging

```sh
[bundle exec] fastlane ios staging
```

Submit a new staging build to Firebase testers...

### ios beta

```sh
[bundle exec] fastlane ios beta
```

Once staging is approved, submit a production build to TestFlight testers...

### ios release

```sh
[bundle exec] fastlane ios release
```

Once beta is approved, promote beta build to App Store...

----


## Android

### android build_application

```sh
[bundle exec] fastlane android build_application
```



### android develop

```sh
[bundle exec] fastlane android develop
```

Development...

### android staging

```sh
[bundle exec] fastlane android staging
```

Submit a new staging build to internal testers...

### android internal

```sh
[bundle exec] fastlane android internal
```

Submit a new production build to internal users...

### android beta

```sh
[bundle exec] fastlane android beta
```

Once staging is approved, submit a production build to beta testers...

### android release

```sh
[bundle exec] fastlane android release
```

Once beta is approved, promote beta build to production...

----

This README.md is auto-generated and will be re-generated every time [_fastlane_](https://fastlane.tools) is run.

More information about _fastlane_ can be found on [fastlane.tools](https://fastlane.tools).

The documentation of _fastlane_ can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
