# Expo CLI Android Build Failure: Missing or Misconfigured Build Tools

This repository demonstrates a common issue encountered when building Android apps using the Expo CLI:  failures due to problems with the Android SDK, NDK, or build tools. The `bug.js` file simulates the scenario where the build process encounters missing or misconfigured build tools, resulting in a failed build. The `bugSolution.js` file provides a solution outlining the steps to verify and correct Android SDK, NDK, and build tools installation and environment variable configuration.

## Bug Reproduction

1. Clone this repository.
2. Follow the instructions in the `bug.js` file to attempt to build an Expo Android project (you will likely need a correctly configured Expo project to reproduce).
3. Observe the build failure.

## Solution

Refer to the `bugSolution.js` file for troubleshooting steps and corrective actions. This includes verifying that:

* The Android SDK, NDK, and build-tools are installed correctly.
* Environment variables like `ANDROID_HOME`, `ANDROID_SDK_ROOT`, and `PATH` are set up properly and point to the correct locations.
* SDK manager is used to install needed build tools
* The correct versions of the Android SDK, NDK, and build-tools are being used.

By carefully following the steps in `bugSolution.js`, you should be able to resolve the build failure and successfully build your Android Expo project.