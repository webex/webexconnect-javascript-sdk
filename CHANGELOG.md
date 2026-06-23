## v1.9.0

### New Features

- **Dynamic Loading**: Directly load the asset config at runtime instead of having to read from a static `imi-environments` file.
- **Multi-App Support**: Use different assets at the same time in different tabs, or switch between assets within the same tab.
- **Asymmetric JWT Token Exchange Mode**: Exchange the client's generated JWT  for a short-lived access token, use it for authorization, maintain the token lifecycle, and handle retries.

### Enhancements

- **Ping-Pong Keep-Alive**: Added a Ping-Pong mechanism between the SDK and the Service Worker to prevent the Service Worker from being killed due to idleness.
- **Bug Fixes**: Fixed minor bugs.

---

## v1.8.0

### Enhancements

- **Minified SDK Format**: The SDK is now delivered in a minified format for improved performance and reduced bundle size. The Connect configuration file is no longer bundled with the SDK. Please refer to the Quick Start Guide for updated integration steps.
- **Simplified Firebase Manifest**: The dynamic manifest_.json file has been deprecated and replaced with a static manifest.json file. This simplifies configuration and aligns with standard Firebase documentation.

