---
title: Local Builds
description: 
position: 2
publish: true
slug: local-build
---

# Local Builds

Build your apps locally on your machine with the help of previously installed development tools and SDKs.

> To build iOS apps locally, you need to run {{ site.ns-sk }} on a macOS system.

## Prerequisites

* Verify that you have configured your machine for local development. For more information, see [Install iOS and Android Requirements for Local Builds]({% slug installation %}#step-3-install-ios-and-android-requirements-for-local-builds).
* To build for iOS, you need a valid certificate and mobile provision. If you have a Free Apple Developer account, you can use the [Code Signing Assistance]({% slug code-signing-assistance %}) to automatically generate temporary certificate and mobile provision. For more information about iOS code signing, see the [iOS Developer Program article]({% slug ios-developer-program %}).
* To build for Android in Release configuration, you need a valid Google Play self-signed code signing identity.

## Procedure

1. Launch {{ site.ns-sk }}.
1. From the top toolbar, select **Run** &#8594; **Build**.
1. Select a target platform.
1. Under **Build Type**, select **Local Build**. 
1. Select a **Configuration**.
1. (Optional) If any issues are present, resolve them before you continue.
1. Click on **Build**.
1. Once the build process is complete, you will be presented with a path to the produced `APK` (for Android) and `IPA` (for iOS) files.
	* When you build for Android, you will see a QR code as well. On a physical device, use a barcode scanner to scan the QR code and install the application.