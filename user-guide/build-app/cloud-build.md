---
title: Cloud Builds
description: 
position: 1
publish: true
slug: cloud-build
---

# Cloud Builds

With {{ site.ns-sk }}, you can build your apps in the cloud and utilize its power and flexibility to achieve a truly cross-platform mobile development on all major desktop operating systems. This includes iOS development on operating systems other than macOS. You do not require any preliminary setup to build your mobile apps in the cloud.

The cloud builds are incremental, which ensures that every build after the first one will take significantly less time to complete. This is possible because some of the app data is cached during the first build and then reused in later builds. 

## Prerequisites

* To build for iOS, you need a valid certificate and mobile provision. If you have a Free Apple Developer account, you can use the [Code Signing Assistance]({% slug code-signing-assistance %}) to automatically generate temporary certificate and mobile provision. For more information about iOS code signing, see the [iOS Developer Program article]({% slug ios-developer-program %}).
* To build for Android in Release configuration, you need a valid Google Play self-signed code signing identity.

## Procedure

1. Launch {{ site.ns-sk }} and open your app.
1. From the top toolbar, select **Run** &#8594; **Build**.
1. Select a target platform.
1. Under **Build Type**, select **Cloud Build**.
1. (Optional) Enable **Clean Build**. You might want to use this option if you experience sporadic build failures or other unexpected behavior. 
1. Select a **Configuration**.
1. (Optional) If any issues are present, resolve them before you continue.
1. Click on **Build**.
1. Once the build process is complete, you will be presented with a path to the produced `APK` (for Android) and `IPA` (for iOS) files.
	* A successful build for Android will produce a QR code as well. On a physical device, use a barcode scanner to scan the QR code and install the application. 




