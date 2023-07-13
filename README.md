<p>
  <a href="https://docs.expo.dev/versions/latest/sdk/sqlite/">
    <img
      src="../../.github/resources/expo-sqlite.svg"
      alt="expo-sqlite"
      height="64" />
  </a>
</p>

# Info
This package is an effort to provide a truly stable version of [`expo-sqlite`](https://www.npmjs.com/package/expo-sqlite) for Expo SDK 49. This package does not sacrifice older stable features for new experimental ones. Note that the utility of this package depends on how the experimental Promise-based API fares in `expo-sqlite`. The hope is that I can deprecate this package once said API becomes stable.

# Everything below this point is documentation from [`expo-sqlite`](https://www.npmjs.com/package/expo-sqlite) (except for installation instructions)

# Overview
Provides access to a database that can be queried through a WebSQL-like API (https://www.w3.org/TR/webdatabase/). The database is persisted across restarts of your app.

# API documentation

- [Documentation for the main branch](https://github.com/expo/expo/blob/main/docs/pages/versions/unversioned/sdk/sqlite.mdx)
- [Documentation for the latest stable release](https://docs.expo.dev/versions/latest/sdk/sqlite/)

# Installation in managed Expo projects

For [managed](https://docs.expo.dev/archive/managed-vs-bare/) Expo projects, please follow the installation instructions in the [API documentation for the latest stable release](https://docs.expo.dev/versions/latest/sdk/sqlite/).

# Installation in bare React Native projects

For bare React Native projects, you must ensure that you have [installed and configured the `expo` package](https://docs.expo.dev/bare/installing-expo-modules/) before continuing.

### Add the package to your npm dependencies

```
npx expo install expo-web-sqlite
```

### Configure for iOS

Run `npx pod-install` after installing the npm package.

### Configure for Android

No additional set up necessary.

# Contributing

Contributions are very welcome! Please refer to guidelines described in the [contributing guide](https://github.com/expo/expo#contributing).
