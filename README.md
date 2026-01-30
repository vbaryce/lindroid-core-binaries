# LinDroid Core Binaries

This repository hosts the cross-compiled QEMU binaries for the LinDroid Pro Android application.

## Binaries
- **aarch64**: For standard Android devices (ARM64)
- **x86_64**: For Android Emulators and ChromeOS

## Build & Release
The binaries are built automatically via GitHub Actions upon creating a new Release.

### How to trigger a build:
1. Click here: [**Create New Release**](https://github.com/vbaryce/lindroid-core-binaries/releases/new)
2. Tag version: `v1.0.0`
3. Title: `v1.0.0`
4. Click **Publish release**

GitHub Actions will automatically build and upload the ZIP files.
