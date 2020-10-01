## React Native Playground Native Runner:

Browse and test React Native apps from rnplay.org on Android or iOS devices.

### Release instructions for contributors:

#### iOS:

Before release, make sure the `main.jsbundle` is being loaded in AppDelegate.m, and NOT the local development server.

Check the `React.xcodeproj` build settings, and make sure RCT_DEV, RCT_DEBUG, DEBUG and RCT_NSASSERT are set to 1 on the `Release` configuration.

